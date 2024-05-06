# Exno:1 Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
```
DEVELOPED BY: SRI SAI PRIYA.S
REG NO.: 212222240103
```
# 1.Read and Display Dataframe

![308787257-17bfa5f0-8e3e-4788-9fa6-b30ec1fa2d6e](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/722edb75-603f-4433-97d7-0a7316d7ac4c)

# Output

![308787369-e39ad9a4-c7c7-4d70-aa4a-7342f8d71429](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/36fd615c-d39d-42c4-af0b-918ffc6f6e3d)

# 2.Display Head

![308787537-02ca8ab8-cc92-4dbc-a1ba-42a52c14a6a9](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/b29e1f05-67d2-4def-98b2-82a308dca4f2)

# Output

![308787636-9d221eb7-3374-4216-be10-896ef7514902](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/84318f8d-ee6f-4682-ac28-4a702961ade4)

# 3.Display Tail

![308787777-2f60d737-7114-4ea2-879b-bdcf4be83765](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/777278c5-1724-43b1-ad41-8beb907e05f9)

# Output

![308787871-52a8e4d1-2a96-4d51-ba93-ce8752a8ca25](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/38cf94dd-7d79-423e-93a6-63684ffa721c)

# 4.Info of DataFrame

![308787993-bedefbdb-de71-49c5-bcb0-3e32209ccb2f](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/ff24deac-f1dd-4242-8baf-83570401811c)

# Output

![308788081-b983145e-fc05-41b8-8799-023f84d2ffc4](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/c21d324c-d182-42f1-a5fa-86455c09b42c)

# 5.Describe about Dataframe

![308788239-4e31132e-ddf8-4129-a6f3-717a1b7c6dad](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/80e721a8-cf8c-4baa-a800-da27c319436f)

# Output
![308788332-5aff5bfc-4624-4e7b-97a9-7e2415c50a64](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/f9b30e01-58d6-4f56-9f99-7e609f9c6851)

# 6.Shape of the dataframe

![308840841-4e35144b-922d-43a1-ba84-57299a8d5914](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/833442fc-4564-4690-bad8-d9cea03a7fc5)

# Output

![308840973-a9a58572-d402-4367-b3be-76a7d2e3ee65](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/74c27975-f17d-4b3f-9f1b-993559643b61)

# 7.Checking tha NUll values

![308841164-860e00fb-88b8-4c81-a9e2-9af250457007](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/d6c04817-b10f-4282-a7f3-33e8612ffe0b)

# Output

![308841277-46c14197-5b6b-4cdd-830e-d7b9870e8f46](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/69b5701a-2190-4d86-9c77-a819695cc3e6)

# 8.Drop the Null values

![308841456-216c68b1-2d00-4054-b0ad-6daa53058024](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/2bc7d7f3-38c9-4f44-b7a0-de54dff51e36)

# Output

![308841593-f9ad02c7-1256-4650-bb9f-d5b55da1471a](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/08a58c81-6769-4699-b415-36e18af29871)

# 9.Drop the Null values in Total

![308841987-a93ff3d6-0f45-43ab-8bd5-3be113e84170](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/19d4141b-fb02-4ecc-a149-c0f249c96a9e)

# Output

![308842552-57a542a3-415f-464f-9229-c6b96bfd047a](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/82efe054-ee65-40a5-9586-cc90505a2599)

# 10.Determinig the Duplicates

![308843571-3c4e1ba6-47e7-44d4-91c9-e37dfff5e8a1](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/77c46595-4d85-4bfb-8572-dbd2743fd8b1)

# Output

![308843703-869c9a72-ffe2-48cb-85fc-b84a0846e2a4](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/76c9d8d6-7aab-4f35-8a99-d906d14f3d36)

# 11.Deleting the duplicates

![308844765-efbabc0f-9cf8-4dd8-8c60-caea3e10d869](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/f11e4613-540f-4414-b0ff-98717fb283ce)

# Output

![308844908-5d95fa7b-3a2d-4e52-bd58-771dfc5f4555](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/d0b7e543-799d-4ffd-bf13-6232a71c513c)

# 12.Highlighting Null values

![308846170-1ff7e73b-f5ca-46e8-b841-e0e06fda57bb](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/e00d9496-e748-44b1-b2a5-4a2917b0cdc8)

# Output

![308846389-e4ffd3df-b29c-4125-bfe9-f12eb1e8fc64](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/f4be239f-6cd4-4ed7-ae21-6058aaf57acc)

# 13.Dropping Null vales

![308846578-0bdc3bec-358c-4e44-af13-8b6c6535b2b3](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/cbbd5c59-3d4d-4e90-8912-1f5222d9d668)

# Output

![308846686-3270d8e2-5e32-4045-91b7-1e5136d58911](https://github.com/SriSaiPriyaSenthilvel/exno1/assets/119475702/fec24983-e73e-4263-a76b-971c8dac251d)

# Result
          The data cleaning has beeen performed successfully.
