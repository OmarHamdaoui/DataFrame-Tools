# split_dataframe

* Split a DataFrame into chunks (with equal pieces by removing the pieces that do not contain the same size as the others)

* It's a CSV file that contains 365 days of data example with columns, so we are going to split this DataFrame into chunks and each peace will be equal to all the others pieces, the rest of the file will be droped, but you can use the "else" condition to conserve it and to get another chunks that will not equal the others chunks or pieces.