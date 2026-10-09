# Reflection

For this project, I created an interactive 8-bit integer overflow visualizer to make the idea of overflow easier to understand. I chose integer overflow because it is easier to understand when you can directly see how a value changes after it is limited to a fixed number of bits.

The application lets the user enter a value, move a slider, or select preset examples. It then shows the stored 8-bit pattern along with the signed, unsigned, and hexadecimal interpretations. Building the visualizer helped me better understand that overflow is not just a number becoming "too large." The stored bits are limited to a fixed width, and those same bits can represent different values depending on whether they are interpreted as signed or unsigned.

My workflow was to first decide what information would be most useful for teaching the concept, then use AI assistance to help generate the initial HTML, CSS, and JavaScript. After that, I ran the application in a browser and tested values such as 127, 128, 255, 256, and -1 to make sure the output matched the expected 8-bit behavior. I also adjusted the layout so the bit pattern and converted values were easy to read.

Overall, this project helped connect the arithmetic overflow concepts from class to a visual example. Seeing the exact bit pattern and how it changes across signed and unsigned interpretations made the concept much clearer than only looking at the arithmetic.