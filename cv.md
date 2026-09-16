# Veranika Zhuk

## Cotact information
**Location:** Wrocław, Poland\
**Email:** zhuk.veranika.2001@gmail.com\
**GitHub:** leviko2\
**LinkedIn:** Veranika Zhuk

## About me
I am currently learning to become a frontend developer. With a background in architecture, I bring a strong eye for design, structure, and spatial thinking — including hands-on experience with 3D modeling and architectural visualization tools.

I am motivated to grow as a developer, improve my technical skills, and build useful and accessible web interfaces, while continuing to apply my 3D modeling background to visual and interactive projects. I enjoy learning and exploring new tools and technologies.

## Skills
**Hard skills:**  
+ **Frontend** (currently learning)**:** HTML, CSS, JavaScript, Git basics, responsive design
+ **Version Control & Dev Tools:** Git, GitHub
+ **3D Modeling & Architecture Software:** Blender, AutoCAD, ArchiCAD, Revit
+ **Design Tools:** Figma, Adobe Photoshop, Canva
+ **Office & Collaboration:** Microsoft Word, Excel, PowerPoint, Teams
+ **AI Tools:** Claude, ChatGPT, Midjourney

**Soft skills:**  
+ Attention to detail 
+ Structured thinking
+ Fast learner

## Code exsampe
**Decimal-to-Binary Conversion** \
A small JavaScript function that converts a non-negative decimal integer into its binary representation, returned as an integer (e.g. for a task where the binary representation of b must equal the decimal representation of d):

```
function toBinary(n){
  
  //return 0 when n=0
  if (n === 0) {
    return (0);
  }
  
  let reverseBinary = '';
  
  //when n > 0 --> get the inverted number using remainder method of division by 2
  while (n > 0) {
    reverseBinary += n % 2;
    n = Math.floor(n / 2);
  }
  
  //convert string to an array, reverse the order of array elements, join array elements to a string
  const binaryString = reverseBinary.split('').reverse().join('');
  
  //make a number out of a string
  const binary = parseInt(binaryString);
  
  return binary;
}
```

## Projects experience
**Markdown CV Project**\
Created this CV using Markdown format.  
Skills used: Markdown syntax, structured content organization, technical writing.

## Education
**Bachelor's degree in Architecture 2020–2025**\
Wrocław University of Science and Technology

**Frontend Development (2025–present):**\
Self-taught track + RS School fullstack-engineering course
* Learning HTML, CSS, and JavaScript fundamentals
* Studying Git and GitHub for version control and collaboration
* Practicing problem-solving through JavaScript challenges on Codewars
* Building small projects to apply learned skills
* Following structured learning paths and open-source resources
* Reading official documentation to understand best practices
* Keeping personal notes and documenting learning progress

## Languages
**English language:** \
Level: B2 (upper-intermediate)\
Language practice: university English coursework; ongoing exposure through English-language educational videos (general topics, not only tech)

**Other languages:**  
+ Russian: Native
+ Polish: C1 (advanced)
+ Belarusian & Ukrainian: Passive understanding