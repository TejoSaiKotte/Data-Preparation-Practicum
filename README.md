# Data-Preparation-Practicum
2023GFA_ANA_515P_01 Exp Practicum


# This is a data preparation process on Election Survey dataset.



    Gender Processing:
        It starts by defining a function group_genders that categorizes gender values into three categories: "Male," "Female," and "Other." This function is then applied to the "Gender" column in the dataset, and a new column "GroupedGender" is created to store the grouped values.
        A bar plot is generated to visualize the distribution of gender categories.

    Country Processing:
        Rows with empty cells in the "Country" column are removed from the dataset.
        A table of unique countries and their counts is created, followed by a bar plot to visualize the distribution of countries.

    Self-Employed Processing:
        Rows with empty cells in the "self_employed" column are removed from the dataset.
        A table is created to count the occurrences of "No" and "Yes" in the "self_employed" column.

    Family History Processing:
        Rows with empty cells in the "family_history" column are removed from the dataset.
        A table is created to count the occurrences of "No" and "Yes" in the "family_history" column.

    Treatment Processing:
        Rows with the value "-" in the "treatment" column are removed from the dataset.
        Values "N" are replaced with "No," and values "Y" are replaced with "Yes" in the "treatment" column.

    Remote Work Processing:
        Rows with the value "-" in the "remote_work" column are removed from the dataset.
        A table is created to count the occurrences of "No" and "Yes" in the "remote_work" column.

    Tech Company Processing:
        Rows with the value "-" in the "tech_company" column are removed from the dataset.
        A table is created to count the occurrences of "No" and "Yes" in the "tech_company" column.

    Benefits Processing:
        Rows with empty cells in the "benefits" column are removed from the dataset.
        A table is created to count the occurrences of different categories in the "benefits" column. The categories are grouped into "Not sure," "No," and "Yes" using a custom function.

    Care Options Processing:
        Rows with empty cells in the "care_options" column are removed from the dataset.
        A table is created to count the occurrences of "No," "Not sure," and "Yes" in the "care_options" column.

    Wellness Program Processing:
        Rows with empty cells in the "wellness_program" column are removed from the dataset.
        A table is created to count the occurrences of "No," "Not sure," and "Yes" in the "wellness_program" column.

    Seek Help Processing:
        Rows with empty cells in the "seek_help" column are removed from the dataset.
        A table is created to count the occurrences of different categories in the "seek_help" column. The categories are grouped into "Not sure," "Other," and "Yes" using the same custom function as for "benefits."

    Removing Empty Rows:
        Rows with empty cells in several other columns are removed from the dataset.

The code is essentially preparing the data for analysis by cleaning and categorizing the values in various columns to make it more manageable for subsequent data analysis tasks.
