Descrierea proiectului:

Proiectul este format din jocul propriu-zis, solver-ul, calculul mediei de încercări și precalcularea celui mai bun cuvânt ca primă încercare. 

Wordle_Game conține fișierele game și solver care reprezintă jocul și algoritmul care ghicește optim cuvântul. 
Pentru rularea programului va fi necesară instalarea modulului Colorama
Pentru VS Code, va fi nevoie de introducerea comenzii 'pip install colorama' in terminal(si implicit existenta extensiei python pentru VS Code)
Pentru PyCharm, noi am folosit site-ul urmator pentru indrumare:https://blog.finxter.com/how-to-install-colorama-in-python/

Programul are două moduri de joc: automat (jucătorul este calculatorul) sau manual (jucătorul este omul).
Best_First_Guess conține programul care calculează și afișează în entropy.out entropia tuturor cuvintelor inițiale și îl alege pe cel cu entropia cea mai mare.
Calcul_medie începe prin folosirea cuvântului TAREI (best first guess), continuând să folosească același algoritm utilizat în Best_First_Guess pentru lista de cuvinte actualizată. 
În solutii.txt se găsesc încercările necesare pentru ghicirea fiecărui cuvânt din listă și la final media de încercări.

Nr. mediu de încercări: 4.372882835690588

Referințe: 
    Solving Wordle using information theory: https://www.youtube.com/watch?v=v68zYyaEmEA
    Oh, wait, actually the best Wordle opener is not “crane”…: https://www.youtube.com/watch?v=fRed0Xmc2Wg
    Information Theory Applied to Wordle: https://towardsdatascience.com/information-theory-applied-to-wordle-b63b34a6538e
    Maximising Differential Entropy to Solve Wordle: https://aditya-sengupta.github.io/coding/2022/01/13/wordle.html
    Colorama: https://pypi.org/project/colorama/
