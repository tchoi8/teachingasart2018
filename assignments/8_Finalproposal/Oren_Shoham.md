# Final Project Proposal: A Gentle Introduction to Shaders

[Fragment shaders](https://thebookofshaders.com/01/) are programs that generate images on a computer's GPU by computing the color of each pixel on the screen simultaneously. Shaders are a powerful tool for creative coding, game development, and video performance, but they also have a reputation for being an intimidating, esoteric subject that requires advanced coding skills and math knowledge to learn. I've been studying shaders on my own for the last several months, and I'd like to share what I've learned in an introductory workshop that attempts to make the topic more accessible, from the perspective of someone who was very recently also a complete beginner.

My goal for the workshop is for participants to walk away understanding what a shader is, able to read and understand other people's shader code, and maybe even able to write their own simple shaders.

This workshop will be aimed at people with a basic understanding of programming and an interest in computer graphics. Since most students at ITP take an [Introduction to Computational Media](https://github.com/ITPNYU/ICM-2017) class in their first semester, I'll plan the workshop with the assumption that participants will already be familiar with things like variables, if statements, and functions.

The workshop will cover the basics of the GLSL programming language, as well as an explanation of the differences between computation on the CPU vs. the GPU and why shaders are fast. I won't try to go over topics like OpenGL/WebGL or vertex shaders, because an hour isn't really enough time to include those as well.

I'm planning on using [editor.thebookofshaders.com](http://editor.thebookofshaders.com/), a browser-based shader code editor, for in-class GLSL examples, so that participants don't have to install anything beforehand.

I'll also prepare some code examples ahead of time that demonstrate the concepts that we discuss, and also show how to use shaders in various creative coding frameworks, such as Processing, p5.js, Three.js, openFrameworks, and Max/MSP/Jitter. These examples will be shared on a public GitHub repo so that workshop participants can review them later.

## References

[_The Book of Shaders_, Patricio Gonzalez Vivo](https://thebookofshaders.com/)

[_Intro to Shaders_, Craig Pickard](https://github.com/Craigson/Intro_to_shaders)
