# 42_Fractol_Resources

teste123

# 42_Fractol_Resources
> Computer Graphics Fractals

## Introduction 
### Discovery
Fractals were discovered by Pierre Fatou and Gaston Julia while studying complex mathematical systems at the turn of the 20th century. 

### Origin of the Term
Fractals resisted linear analysis due to their unlimited complexity and consequent heavy computational requirements. Thus they were forgotten until Benoit B. Mandelbrot, a polish-born mathematician, coined the term while working at IBM’s Armonk, New York labs in the 60s.

### Fractals throughout History
**17th Century : Gottfried Leibniz**
- Studied recursive self-similarity. He used the term ‘fractional exponents’ to refer to the scaling properties and lamented that "Geometry" did not yet know of them. [^1]
- Interest in fractals waned after Leibniz, the few who studied the topic called them “mathematical monsters.”

> [!Note]
> He believed that just a straight line was also self-similar, but in our modern understanding, we do not consider that a fractal.

**18th of July, 1872 : Karl Weierstrass**
- At the Royal Prussian Academy of Sciences, he discovered a special function now named after him.
- This function is everywhere continuous but nowhere differentiable. [^2]

**1883 : Georg Cantor**
- Attended lectures by Weierstrass. 
- He studied subsets of the `real line` that we now call `Cantor sets`. These lines are self-similar and follow the pattern by removing sections. 

**Late 1800s : Henry Poincaré & Felix Klein**
- Discovered what we now call “self-inverse” fractals.

**1904 : Helge von Koch**
- The Swedish mathematician disagreed with Weierstrass' definition that fractals were continuous but not differentiable.
- Starting from Poincaré ideas, he instead suggested a definition from from "Geometry". He created hand-drawn images of an identical repeating pattern that we now know as the `Koch snowflake`. [^3]

**1915 : Waclaw Sierpinski**
- Created what we know today as the Sierpinski Triangle.

**1918 : Pierre Fatou & Gaston Julia**
- Working independently, the two french mathematicians arrived practically simultaneously at the same results relating their studies of dynamics, atractors, repellors and the complex number plane;
- They described what is now seen as fractal behavior associated with mapping complex numbers and iterative functions and leading to further ideas about attractors and repellors (i.e., points that attract or repel other points), which have become very important in the study of fractals.
- Today we call this field `Chaos Theory`.

**March 1918 : Felix Hausdorff**
- Made another important contribution to the field of fractals expanding the definition of "dimension" significantly, allowing for sets to have non-integer dimensions.

**1938 : Paul Lévy**
- Made important contributions to stochastic processes, random walks, and probability while expanding on self-similar curves now known as Lévy C curve. 

**1960s : Benoit Mandelbrot**
- Originally used printers to create the graphics that he required to study the fractal dynamics of attractors. Later, he would use computer screens as the technology caught up with his ideas. [^4]
- Mandelbrot used fractal ideas to advance the study of physical objects, probability, stock market behavior, and dynamics. Fractal geometry also drove the miniaturization of cell phones. [^5]

**1980s : Loren Carpenter**
- Created software for producing and visualizing fractal landscapes. This method is used often today to generate realistic-looking landscapes in video games.

### Fractal Timeline
|         Mathematician          | Timeline Date |                       Discovery                        |
|:------------------------------:|:-------------:|:------------------------------------------------------:|
|       Gottfried Leibniz        |   1650-1700   |               Discovers self-similarity                |
|        Karl Weierstrass        | 18 July, 1872 |              Invents Weierstrass function              |
|          Georg Cantor          |     1883      |              Discovers Cantor Set Fractal              |
| Henri Poincare and Felix Klein |     1880s     |           Creation of Self-Inverse Fractals            |
|         Helge von Koch         |     1904      |         Makes and presents the Koch Snowflake          |
|       Waclaw Sierpinski        |     1915      |          Invention of the Sierpinski Triangle          |
| Pierre Fatou and Gaston Julia  |     1918      |         Study iterative functions and dynamics         |
|        Felix Hausdorff         |     1918      |     Creates the measurement of Hausdorff dimension     |
|           Paul Levy            |     1938      |              Creation of the Levy C Curve              |
|       Benoit Mandelbrot        |     1960s     | Develops cohesive fractal theory in a series of papers |
|       Benoit Mandelbrot        |     1975      |                 Coins the term Fractal                 |
|        Loren Carpenter         |     1980      |            First Fractal Landscape rendered            |

___
## Using Fractals
Fractal mathematics has numerous applications, including Chaos Theory and the study of complex dynamic systems, creating computer images, file compression, studying the architecture of digital networks, and even the diagnosis of various diseases.

Their use cases are wide-ranging and can be found implemented in many day-to-day devices.

### Fractals in Geometry 
Fractal geometry and the ability to measure the Hausdorff dimension of collected data may be used to comprehend the complexity of systems and shapes.

Fractal geometry can describe unpredictable phenomena in various ways.

These types of distributions are called Power Laws and were a favorite subject of study for Levy. These include earthquake timing and size, variations in a person’s heartbeat, and the occurrences of diseases and death.

### Fractals in Art
Fractals have also been used in the arts. Images formed by fractals are intricate yet alluring, they have longed drawn artists' curiosity.

Artists such as Jackson Pollock and Max Ernst have produced apparently chaotic yet defined compositions. It has been shown that there is a measurable Hausdorff dimension in their work. [^6]

### Fractals in Biology
Fractals have a significant role in biological research, as natural systems often follow fractal shapes. (i.e. Blood vessels have a self-similar structure.)

Fractals are also capable of modelling other types of networks like neural networks and the nervous systems of a variety of animals.

### Fractals in Imaging
One of the most common applications of fractals is image compression. Pixel data in an image can be expressed as an iterative system of functions. This allows for the storage of the image to be recorded as a much smaller number of parameters. This image still appears fast and renders itself in great detail at any magnification (due to the scaling property of fractals).

___
## Fractals in Nature
The branching behavior that gives plants a self-similar shape also gives fractal repetition to trees, roots, leaves, ferns, and the fungal mycelium. [^7]

Geography often displays fractal shapes. This was the key connection made by Carpenter in his landscape generation software. Fractals can also be found describing the patterns of streams, rivers, coasts, mountains, waves, waterfalls, and water droplets in the natural world.

### Growth Spirals
Growth spirals, which follow the Fibonacci Sequence (aka. the Golden Spiral) and can be considered as a special case of self-similarity, also contain fractal patterns. The fractal pattern that is known as the Dragon Curve also relates to the Fibonacci Sequence since its Hausdorff dimension is the number φ (1.61803). 

### Fractal and Technology  [^8]
`Modern cell phones` use a fractal antenna shape to work at multiple frequencies at the same time. Different antenna forms correlate to various radio bands that carry cell phone signals within the antenna.

Since these shapes are embedded within one another, multiple different frequencies can be used simultaneously in a cell phone.

According to research, fractal antennas outperform standard-shaped antennas, such as the old-fashioned whip antenna that used to be found mounted on cars.

`Fractal image compression` has been researched as a way to enhance the JPEG algorithm. JPEG uses the `Discrete Cosine Transform` method which represents the image’s information in terms of frequency instead of pixel values. Since cosines are self-similar in shape, fractal image compression algorithms can then be used to recognize scaling patterns. These scaling patterns can then express the same frequency information as a smaller set of parameters for an iterated function system. Fractal image compression is also used in the compression of satellite data. 

If you can find repeated patterns in the data, you can use fractal equations for summarizing them, which are faster to communicate wirelessly than every pixel in the raw image.

___
## Fractal Sets

Julia & Mandelbrot Sets are defined by: 

> $Z_{n+1} = Z_{n} + c$

Z = a Complex number at n-th iteration;
c = Constant complex number corresponding to a point in the complex plane.
### The Mandelbrot Set
Was discovered by Benoit B. Mandelbrot while investigating mappings of the function:
> $f(z) = z^2 + c$

Is generated by iterating a simple function on the points of the complex plane. 
- Points that `produce a cycle` (the same value over and over again) fall in the set;
- Points that `diverge` (give ever-growing values) lie outside it [Different colors represent different rates of diversion].
#### Generating the Mandelbrot Set

- Start from point $Z_0$ of the complex plane;
- Use the quadratic recurrence equation $Z_{n+1} = Z_{n}^2 + Z_{0}$ to obtain a sequence of complex numbers $Z_{n}$;

> - The points $Z_{n}$ are said to form the orbit of $Z_{0}$;
> - The Mandelbrot set, denoted by `M` is defined:
> 
> If the orbit $Z_n$ fails to go to infinity, 
> 	we say that $Z_{n}$ is contained within the set $M$.
> If the orbit $Z_n$ does go to infinity, 
> 	we say that the point $Z_{0}$ is outside $M$.

### The Julia Set

___
## Fractal Generation Techniques
### Escape-Time Fractals
### Iterated Function Systems
### Random Fractals
### Orbit Trap Method


___
# Refs
## Docs
- [fractalfoundation.org/fractivities/FractalPacks-EducatorsGuide.pdf](https://fractalfoundation.org/fractivities/FractalPacks-EducatorsGuide.pdf)
## Articles
- [Fractal - Wikipedia](https://en.wikipedia.org/wiki/Fractal)
- [History of Fractals](https://nnart.org/history-of-fractals/)
- [What is Wonderdraft?](https://nnart.org/what-is-wonderdraft/)
- [Understanding Julia and Mandelbrot Sets](https://www.karlsims.com/julia.html)
- [Tag: Complex Numbers — Acko.net](https://acko.net/tag/complex-numbers/)
- [Complex Analysis](https://complex-analysis.com/content/mandelbrot_set.html)
### Real Numbers 
- [Real Numbers (Definition, Properties and Examples)](https://byjus.com/maths/real-numbers/)
### Value of i
- [Value of i in Complex Numbers - Powers of i Chart](https://byjus.com/maths/value-of-i/)
- [Value of I - Commonly Used Values of i](https://www.vedantu.com/maths/value-of-i)
## Repos
- [fract-ol: graphically beautiful fractals | Medium](https://medium.com/@leogaudin/fract-ol-creating-graphically-beautiful-fractals-6664b6b045b5)
- [fract-ol — render beautiful sets. | by Braulio Santos | Jan, 2024 | Medium](https://medium.com/@by1jorgesantos/fract-ol-render-beautiful-sets-0699a378b953)
## Tools
- [Online graphing calculator — NumWorks](https://www.numworks.com/simulator/)
## Videos
- 
## LaTeX
- https://wch.github.io/latexsheet/latexsheet-0.png
- [users.dickinson.edu/\~richesod/latex/latexcheatsheet.pdf](https://users.dickinson.edu/~richesod/latex/latexcheatsheet.pdf)
- [LaTeX/Mathematics - Wikibooks, open books for an open world](https://en.wikibooks.org/wiki/LaTeX/Mathematics)
- [Markdown and LaTeX introduction](https://ashki23.github.io/markdown-latex.html)

## Footnotes

[^1]: [The Fractal Geometry of Nature - Benoit B. Mandelbrot - Google Livros](https://books.google.pt/books?id=0R2LkE3N7-oC&redir_esc=y)
 [^2]: [Are Fractals or Fractal Curves Differentiable?](https://nnart.org/are-fractals-differentiable/)
[^3]: [How to Draw Fractals by Hand: A Beginner's Guide](https://nnart.org/how-to-draw-fractals-by-hand-a-beginners-guide/)
[^4]: [Complete List of Books by Benoit Mandelbrot](https://nnart.org/complete-list-of-books-by-benoit-mandelbrot/)
[^5]: [How Are Fractals Used in Technology and Engineering?](https://nnart.org/how-are-fractals-used-in-technology-and-engineering/)
[^6]: [Style Guide: How Did Jackson Pollock Paint?](https://nnart.org/style-guide-jackson-pollock/)
[^7]: [How Do Fractals Appear in Nature? 10 Outstanding Examples](https://nnart.org/fractals-in-nature/)
[^8]: [How Are Fractals Used in Technology and Engineering?](https://nnart.org/how-are-fractals-used-in-technology-and-engineering/)
