# Molecular-Formula-Elemental-Filter
A function to check if a molecular formula (string) only contains the given elements.
The function return false is the formula contains any other elements which is not in the list

Instructions:

To check if a molecular formula only contains e.g. C, H, O, and Cl. 
Adjust the elements in the function filter_form: 'Cl', 'C', 'H', 'O'
Remark: start with the double string elements such as Si, Br, Cl, etc 

Example:

Formula should only contain the elements: 'Cl', 'C', 'H', 'O' (adjusted in the function)  
  elements = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9', # all digits
              'Cl', 'C', 'H', 'O'] # First the double string elements such as Cl, Br, Si
              
filter_form('C10H22')       --> True  
filter_form('C10H22O2')     --> True  
filter_form('C10H22O2Cl)    --> True  
filter_form('C10H22O2Br)    --> False  
filter_form('C10H22NO2Cl)   --> False  

