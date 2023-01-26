# analysis of challenge 2:

# Purpose of analysis: The purpose was to determine which stocks are more profitable by using the data of both 2017 and 2018. We were able to get results and see volume depending on tickers name. This information can later be used on deeper analysis. 

## Results: it appears that as refactoring this new code I was able to get a faster process time. Using the data there was one issue that bother me about the data and it was the fact that the input box if you added anything to it besides “2017” and “2018” it would take you to the macro for debugging. The following images show results from the module 1 and once I try to refracture it. So I had to create this code

‘On Error Resume Next-(placed right on top of inputbox)
‘On Error GoTo 0-(placed right before formatting code)
and place the following right before the formatting portion of the code.
This allow for if the user inputs something outside the two data sets it will calculate nothing but it would ask him to check the macros. It would just reset the macro and await for a valid entry. The images below show the difference between the times it took for the originals too process to the end result.

<img width="1280" alt="2017 challenge stamp" src="https://user-images.githubusercontent.com/90356052/135817498-90046648-cb77-4dca-a763-3b511bc5f07a.png">
<img width="1280" alt="2017 time stamp " src="https://user-images.githubusercontent.com/90356052/135817517-58893312-2b30-46af-bd1a-b68ca5a4e184.png">
<img width="1280" alt="2018 time stamp challenge" src="https://user-images.githubusercontent.com/90356052/135817523-4d88a739-1a33-430d-8964-d22baa0f7599.png">
<img width="1280" alt="2018 Time stamp" src="https://user-images.githubusercontent.com/90356052/135817527-9cdcd610-7c57-4f18-b637-9f1d74d37540.png">


#Summary:
#Advantages: noticeable advantages of refactoring code are you get to play with the code more and see a different way or more effective methods to perform tasks. It also forces you to explore more the web, especially when you can’t make the code work and you must look for alternatives. Another advantage that I found was that it makes me start thinking automatization. If you can get the code to run itself than the means the least, you must touch the code. 

#Disadvantage: refracturing code can be time consuming, especially if is regarding new code. You also must be careful that you have a backup of your old code. Several times I had to recopy my old code and start again to get my macros to work again. Sometimes there is no luxury of time so keeping track of your changes is needed. 


