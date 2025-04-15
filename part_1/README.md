# Part 1

STEP 1 - Tools:SetVariable node
    - Variable name: Prompt
    - Variable value: “Hello!”

STEP 2 - OpenAI:CreateACompletion node
    - Model: `gpt-4o-mini`
    - Now we add a “User” message
        - “Hello!”
    - Run the automation
    - Test the “Assistant” message
    - Test the “System” message
        - “You are a Social Media marketer known for creating viral, revenue generating content”
    - Go back to the “User” message
    - Notice the overlay menu
    - Reference the prompt for the Tools Module
    - And that’s LEVEL 1

## Remember to connect the OpenAI module

- Signup on platform.openai.com
- Create an API key
- Copy the API key
- Optional: Create an `Organization`
  - Copy the `Organization ID`
