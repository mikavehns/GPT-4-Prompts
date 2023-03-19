<p align="center"><h1>GPT-4 Prompts</h1></p>

<p align="center"><img src="https://user-images.githubusercontent.com/66560242/226178713-db00b770-8e45-4bbc-aab3-4d8f746fed1b.jpeg"></p>

Welcome to the "GPT-4 Prompts" repository! Here, you will find prompts for GPT-4 that utilize its multimodality to produce the best results.

[GPT-4](https://openai.com/product/gpt-4) is a LLM developed by [OpenAI](https://openai.com). One of its key features, inherited from [GPT-3.5/ChatGPT](https://openai.com/blog/chatgpt), is its ability to recognize images.

This repository draws inspiration from [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts). However, since that repository is outdated, I have created a new collection to share GPT-4's new capabilities with everyone.

Each prompt in this repository comes with an explanation of how to use it. You can also [contribute](https://github.com/mikavehns/gpt-4-prompts/edit/main/README.md) by adding your own prompts to this collection.

These prompts are designed to be used on the [OpenAI-Playground](https://platform.openai.com/playground?mode=chat). You will always find a "System" message, which you need to paste into the left input field. Any additional instructions will be provided above the prompt.

---

# Prompts

## Fix code appearance
By: [@mikavehns](https://github.com/mikavehns)

<details>
  <summary>System Message</summary>
> "You are a programming expert. The user will provide you with his code and your task is to format it, so it has a better visual appearance."
 </details>
 
 <details>
  <summary>User Message</summary>
  ```
  Your Code
  ```
  </details>

### Example
<details>
<summary>Input</summary>
```
  def sum (a ,b ) :
#adding two numbers
return( a + b
)
num1 = 5
num2 = 10

#calling function
result= sum (num1, num2)
print("The sum of", num1 , "and", num2 , "is", result)
  ```
  </details>

<details>
<summary>Output</summary>
> Here's the formatted code:
```
  def sum(a, b):
# adding two numbers
return a + b

num1 = 5
num2 = 10
  # calling function
  result = sum(num1, num2)
print("The sum of", num1, "and", num2, "is", result)
  ```
Changes made:
- Removed unnecessary spaces between function name and parameters.
- Added spaces between parameters and commas.
- Added spaces around operators for better readability.
- Removed unnecessary parentheses around return statement.
- Added a blank line after the function definition for better readability.
 </details>
```
  
