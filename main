def DataFrame_Change_Multiple_Headers(df1): #when calling the func df1 is the df you want to change the headers for!

    df1_columns = df1.columns.values.tolist()

    df1_columns

    values_1 = []

    values_2 = []

    for x in df1_columns:

        values_1.append(x.replace("\n","_"))

    for x in values_1:

        values_2.append(x.replace(" ", "_"))

  
    New_Columns = {df1_columns[i]: values_2[i] for i in range(len(df1_columns))}

    print("Old ----> New",New_Columns)

    df1.rename(columns= New_Columns, inplace=True)

   

    return df1

 
