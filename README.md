# Employee Departure Prediction (Supervised Learning)

The dataset is about an organisation and its employees data. The dataset also contains a column that represents whether the employee is currently working in the organisation or not.

After the examination of first few rows and column values, these are our assumptions on the dataset.

    The dataset contains 300K rows and 11 columns.

    Out of 11 columns, 9 columns are relevant to the employee which includes
        Gender
        Distance (away from the company location)
        YearsWorked (in the company)
        PreviousSalary (in the company)
        Salary (Current)
        SelfReview
        SupervisorReview
        DepartmentCode
        Left (label that represents whether employee is the current or former one)

The aim of this project is to use this data to predict the possiblity of an employee leaving the organisation in the near future.

# Employee Departure Prediction (Semi-Supervised Learning)


The project aims to identify employees who are expected to leave the company. Unfortunately, dataset doesn't have the labels.

But the project aims to solve the problem by taking the help of an SME (Subject Matter Expert) who has been working for a long time in the company.

Fortunately, SME labeled the testing data. So after we have finished building the model, we can test the model against the test data.
