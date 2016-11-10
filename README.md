# KlinValidator
This class can validate arrays of values according to given rules.  It can take definitions of rules to be applied to each entry of an array to be submitted with values to validate.  The class can take an array with values to validate with the previously defined rules.  It uses regular expressions to validate values by each rule. Currently it can validate values as email, URLs, IP addresses, integers, floats, booleans, minimum, maximum and exact length, and regular expression matching.  The class stores the resulting validation errors in a class variable.