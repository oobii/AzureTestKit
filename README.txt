https://docs.microsoft.com/en-us/learn/modules/arm-template-test/5-exercise-test-toolkit?pivots=macos

git clone https://github.com/Azure/arm-ttk.git
Import-Module /Users/martynov/code-local/azure/arm-ttk/arm-ttk/arm-ttk.psd1
cd ./AzureTestKit/
Test-AzTemplate -TemplatePath .