### Introduction
Quick overview of how to create dotnet MVC using CLI

## Steps

# 1. download dotnet framework:
https://dotnet.microsoft.com/en-us/download

# 2. install it and then check it's version.
Go to CMD or PowerShell and type:
'''
dotnet --version
'''

# 2.1. it has to show your framework version:
'''
"8.0.100"
'''

# 3. go to desired folder to create your mvc-example and then create your project.
it may take few seconds:
'''
dotnet new -o mvc-example
'''

# 4. go to project folder
'''
cd mvc-example
'''

# 5. compile
'''
dotnet build
'''

# 5.1. if everything is correct, it shows:
'''
Build succeeded.
    0 Warning(s)
    0 Error(s)
'''

6. compile and run
'''
dotnet run
'''

7. add packages
'''
dotnet add <desired_package>
'''