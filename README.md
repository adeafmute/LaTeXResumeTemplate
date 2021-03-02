# LaTeX Resume Template
This is a resume template intended for anyone wanting to get a job. The template was made with cybersecurity in mind, so if certain sections don't apply to you, feel free to remove them and use this template however you wish.

Includes sections for a personal summary, education, clearance/certifications, work experience, related experience, and skills.

See what it looks like as a pdf here:
https://github.com/paulh2019/LaTeXResumeTemplate/blob/main/Resume_Template.pdf

If you don't know how to edit LaTeX or turn it into a PDF, I recommend Overleaf, an online LaTeX editor:
https://www.overleaf.com/

I personally use the Texmaker LaTeX editor: https://www.xm1math.net/texmaker/

Tex Checklist:
1. Change personal details

    a. \myFullName
  
    b. \myEmail
  
    c. \myCityState
  
    d. \myPhone
  
2. Update both \hspace*{} in the header so that your location is centered under your name

3. Fill out remaining sections using the following items:

    a. \shortitem{title}{year}{description}
  
    b. \longitem{title}{year}{description}  
  
    c. \mainSubitem{title}{year}{description}
  
    d. \bulletSubitem{description}
  
    e. \indentSubitem{description}
