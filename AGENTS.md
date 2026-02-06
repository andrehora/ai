# Instructions to create quiz questions

## Types of quiz questions
- Single choice: one correct choice
- Multiple choice: two or more correct choices
- True/false: true and false choices

## Quiz size
- A quiz has between 3 and 5 questions
- A question has between 2 and 5 choices

## Quiz organization
- A quiz must have at least one type of question
- Questions shoud be in the following order: Single choice, Multiple choice, True/false

## Quiz filename
- A quiz should be saved a in `.md` file
- The file should be named with a relevant keyword about the quiz topic without hyphen

## Question description
- Question is prefixed with "#", example, `# What is 2 + 2?`
- Choice is prefixed "-", example, `- 4`
- Each question and choice should be in a line

## Setting the correct choices
- Single choice: the correct choice ends with the character "x", example, `- 4 x`
- Multiple choice: the correct choices end with the character "x", example, `- 4 x`
- True/false:
  - true choices end with the character "t", example, `- 4 t`
  - false choices end with the character "f", example, `- 5 f`

## Examples of questions

### Single choice
```
# What is the capital of France?
- Madrid
- Paris x
- London
- Berlin
```

### Multiple choice
```
# Which of the following cities are in Brazil?
- Rio de Janeiro x
- São Paulo x
- Buenos Aires
- Recife x
```

### True/false
```
# Evaluate these statements about Australia:
- Australia has six states t
- The smallest state in Australia is Tasmania t
- Sydney is the capital of Australia f
```

## Example of a complete quiz

```
# What is the capital of France?
- Madrid
- Paris x
- London
- Berlin

# Which of the following cities are in Brazil?
- Rio de Janeiro x
- São Paulo x
- Buenos Aires
- Recife x

# Evaluate these statements about Australia:
- Australia has six states t
- The smallest state in Australia is Tasmania t
- Sydney is the capital of Australia f
```
