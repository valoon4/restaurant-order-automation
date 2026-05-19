# Restaurant Order Automation

Simple AI-powered restaurant order parsing workflow built with n8n and OpenAI.

## Example Input

2 Margherita pizzas with vegan cheese and one cola without ice

## Example Output

```json
{
  "items": [
    {
      "name": "Margherita Pizza",
      "quantity": 2,
      "modifiers": ["vegan cheese"]
    },
    {
      "name": "Cola",
      "quantity": 1,
      "modifiers": ["without ice"]
    }
  ]
}
