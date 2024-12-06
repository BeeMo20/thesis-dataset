# Thesis dataset
Here you can find all my data used for my thesis.

## Process
The data was collected by giving multiple source codes to the LLM named Gemini and ask if it could find any cyclic dependency in the given source code, each time with diffrent prompts.
Here are the prompts that I used:

## Prompt 1
I have the following Java classes. Do you see any architectural smell? These are the only classes in my project.

Do not explain what is an architectural smell or how to remove it, just say if you see some or not. 

## Prompt 2
I have the following Java classes. Do you see any architectural smell? These are the only classes in my project. I am looking for these architectural smells: Hub-like dependency, Cyclic dependency, God component, Unstable dependency, Cyclic hierarchy, Deep hierarchy, Wide hierarchy.

Do not explain what is an architectural smell or how to remove it, just say if you see some or not.

## Prompt 3
I have the following Java classes. Do you see any cyclic dependency architectural smell? These are the only classes in my project.

Do not explain what is an architectural smell or how to remove it, just say if you see some or not.

## Prompt 4
I have the following Java classes. Do you see any cyclic dependency architectural smell? These are the only classes in my project. In particular, a cyclic dependency architectural smell is formed when two or more components have direct or indirect dependencies on each other. 

Do not explain what is an architectural smell or how to remove it, just say if you see some or not.


