# Here is some Python code I created for my 1040 class

    def get_stats(values):

        num_values = len(values)

        total = 0
        for value in values:
            total = total + value


        average = total / num_values

        return {"num_values":num_values, "total":total, "average":average}


    def main():
        values = []

        try:
            (num, total) =  get_stats(values)
        

            print("num = ", result["num_values"])
            print("total = ", result["total"])
            print("avg = ", result["average"])
        except Exception as error:
            
            print(error)



    main()

Go back to the main page [here](README.markdown)
