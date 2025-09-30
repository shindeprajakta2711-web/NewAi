<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# ElectroIQ

Final project for the Building AI course

## Summary

ElectroIQ is a AI-powered based assistant which will provide you the detailed information about electronic components. Whether it's identitfying the anode or cathode or identifying the resistor's resistance value or IC pin configuration


## Background

Electronics engineering students or even professionals often struggle to find quick, reliable infomation about the components while working on circuits or any live project. My motivation is to build an AI that serves as a knowledge hub for electronics ,making easier to learn and apply concepts in real-time.
This project addresses:
1.Lack of centralized and simplifies information about components.
2.Time wasted in searching across multiple sources.
3.Difficulty for begineers in identifying component terminals and symbols.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://github.com/shindeprajakta2711-web/NewAi/blob/main/ChatGPT%20Image%20Sep%2029,%202025,%2004_17_10%20PM.png?raw=true)

If you need to resize images, you have to use an HTML tag, like this:
<img src="(https://github.com/shindeprajakta2711-web/NewAi/blob/main/ChatGPT%20Image%20Sep%2029,%202025,%2004_17_10%20PM.png?raw=true)">

This is how you create code examples:
```
# Example: Querying ElectroIQ for electronic component details def query_electroIQ(component): knowledge_base = { "LED": { "definition": "A Light Emitting Diode is a semiconductor device that emits light when current flows through it.", "anode": "The longer leg is the Anode (+).", "cathode": "The shorter leg (flat side) is the Cathode (-).", "usage": "Used in indicators, displays, and lighting applications." }, "Resistor": { "definition": "A resistor is a passive component that resists the flow of electric current.", "symbol": "zig-zag line or rectangle depending on standard.", "usage": "Used to limit current, divide voltage, and bias circuits." } } return knowledge_base.get(component, "Component not found in database.") # Example usage print(query_electroIQ("LED")) print(query_electroIQ("Resistor")) print(query_electroIQ("Capacitor")) # Not yet in database
```


# Data sources and AI methods

The data for ElectroIQ comes from a mix of open educational resources and manufacturer documentation.  
These sources provide reliable details about electronic components such as pin configurations, symbols, and usage.

[All About Circuits](https://www.allaboutcircuits.com/)  
[Electronics Tutorials](https://www.electronics-tutorials.ws/)  
[Texas Instruments Datasheets](https://www.ti.com/)  
[NXP Semiconductors Datasheets](https://www.nxp.com/)  

| Data Source                | Purpose                          |
|-----------------------------|----------------------------------|
| All About Circuits          | General electronics concepts     |
| Electronics Tutorials       | Beginner-friendly explanations   |
| Manufacturer Datasheets     | Pin details and specifications   |
| Open-source textbooks       | Theory and practical examples    |

**AI Methods used:**
* **Natural Language Processing (NLP):** to understand user queries (e.g., “What is LED?”).  
* **Rule-based Knowledge Base:** structured facts about components.  
* **Optional ML models:** for future expansion (e.g., identifying components from images).  

## Challenges

1.The AI model’s performance depends heavily on the quality and diversity of the dataset.
2.Misclassification of components can occur, especially for visually similar parts (e.g., resistors of different ratings or ICs with similar appearance).
3.Requires a good camera or sensor for high-resolution image capture.


## What next?

1.For more accurate output we can develop a high resolution camera which will see the component and will develop the visual image as it is on the recorded video
2.It can also detect the wrong connection depending on the components or the title of project.
3.We can also implied the cost effective components for student's project which will be better too and cost effective too
4.We can also build a AI based stimulation .
5.We can also implement the circuit by doing the stimulation as for testing purpose.


## Acknowledgments

## Acknowledgments

I would like to express my gratitude to the following resources and inspirations that helped in shaping this project:

* **Reaktor Innovations & University of Helsinki** – for creating the *Building AI* course that provided the structure and motivation for this project.
* **Open educational platforms** such as [All About Circuits](https://www.allaboutcircuits.com/) and [Electronics Tutorials](https://www.electronics-tutorials.ws/) for their comprehensive resources on electronics fundamentals.
* **Texas Instruments** and **NXP Semiconductors** for making their datasheets openly accessible, which formed the backbone of the component reference material.
* **Open-source communities** that promote knowledge sharing in AI, Python, and electronics.
* Inspiration from educators, mentors, and peers in the field of *Electronics and Telecommunication Engineering* who emphasized the importance of practical tools for learning.


