Navigate to Requirements.txt and install all modules

##### Naming Conventions of PyTest ###########
1) File name should start with "test_LoginTests.py"
2) Method name should start with "test_login"

######## 3 Ways of executing the code in pytest #############

py.test -v -s files_path    # run all tests in specific files_path
py.test -v -s test_mod.py py.  # run tests in module or in test file
py.test -v -s test_module.py::test_method  # only run test_method in test_module.py

-v : verbose (verbose is an argument which is used to report more information about an operation in your program )
-s : to print statements

######## Allure commands #############

attach allure to test execution command: py.test --alluredir=./reports -v -s test_LoginTests.py
generate allure report command: allure serve results#   s m e d i x _ a u t o m a t i o n _ i n t e r n s h i p  
 #   p e r s o n a l - p r o j e c t  
 