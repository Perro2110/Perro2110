<h1 align="center">
  <img src="https://images.vexels.com/media/users/3/220016/isolated/preview/4d541636c1345b26a4e3215054f4e4e6-yellow-rubber-duck-illustration.png" width="50">

  <picture>
    <!-- Tema scuro → testo bianco -->
    <source 
      media="(prefers-color-scheme: dark)" 
      srcset="http://readme-typing-svg.herokuapp.com?weight=800&size=37&duration=2500&pause=1000&color=F7F7F7&center=true&width=435&lines=Hello+World!+;I'm+Marco+Perrotta"
    />
    <!-- Tema chiaro → testo nero -->
    <img 
      src="http://readme-typing-svg.herokuapp.com?weight=800&size=37&duration=2500&pause=1000&color=000000&center=true&width=435&lines=Hello+World!+;I'm+Marco+Perrotta" 
      alt="Typing SVG" 
    />
  </picture>

  <img src="https://images.vexels.com/media/users/3/220016/isolated/preview/4d541636c1345b26a4e3215054f4e4e6-yellow-rubber-duck-illustration.png" width="50">
</h1>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=perro2110&label=Profile+views&color=534AB7&style=flat-square" />
  &nbsp;
  <img src="https://img.shields.io/badge/University-Ferrara-7F77DD?style=flat-square" />
  &nbsp;
  <img src="https://img.shields.io/badge/Focus-Symbolic_AI-1D9E75?style=flat-square" />
  &nbsp;
  <img src="https://img.shields.io/badge/License-Open_Source-BA7517?style=flat-square" />
</p>

---

## `data Developer`

```haskell
import University.Ferrara
import ACLAI.Lab          (sole, symbolicLearning)
import qualified Logic.Symbolic as AI

data Developer = Developer
  { name    :: String
  , origin  :: String
  , uptime  :: Years
  , focus   :: [Topic]
  , hobby   :: [Passion]
  } deriving (Show, Eq)

me :: Developer
me = Developer
  { name   = "Marco Perrotta"
  , origin = "Italy"
  , uptime = 21
  , focus  = ["Symbolic AI", "Machine Learning", "Logic for CS"]
  , hobby  = ["Playing with different OS", "Formal logic", "ML research"]
  }
```

---

## `type Language = Favourite`

```haskell
type Favourite = [Language]

myLanguages :: Favourite
myLanguages = ["Gleam", "C", "Julia", "Haskell"]
  -- naturally a conjunction of passions: ∧ ∧ ∧

toolchain :: [Tool]
toolchain =
  -- languages
  [ "Gleam", "C", "Julia", "Haskell"
  , "Python", "Go", "Java", "Bash", "PHP"
  , "Prolog", "MIPS ASM", "R", "MATLAB", "Fortran"
  , "LaTeX", "HTML", "CSS", "SQL", "Arduino"
  -- frameworks & libraries
  , "Laravel", "scikit-learn", "Angular"
  -- editors & environments
  , "VSCode", "Notepad++", "tmux"
  -- tools & platforms
  , "Git", "WSL", "PuTTY", "TeamViewer", "JAndroid"
  ]
```

<p align="center">
  <!-- favourite languages -->
  <a href="https://gleam.run"><img src="https://gleam.run/images/lucy/lucy.svg" width="40" title="Gleam"/></a>&nbsp;
  <a href="https://www.haskell.org/"><img src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Haskell-Logo.svg" width="40" title="Haskell"/></a>&nbsp;
  <a href="https://julialang.org/"><img src="https://github.com/Perro2110/Perro2110/blob/main/waving-flag.gif" width="40" title="Julia"/></a>&nbsp;
  <a href="https://www.cprogramming.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" width="40" title="C"/></a>&nbsp;
  <!-- languages -->
  <a href="https://go.dev"><img src="https://go.dev/doc/gopher/gopherdrink.png" width="40" title="Go"/></a>&nbsp;
  <a href="https://www.python.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" title="Python"/></a>&nbsp;
  <a href="https://www.java.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40" title="Java"/></a>&nbsp;
  <a href="https://www.swi-prolog.org/"><img src="https://avatars.githubusercontent.com/u/6884283?s=200&v=4" width="40" title="SWI-Prolog"/></a>&nbsp;
  <a href="https://www.gnu.org/software/bash/"><img src="https://bashlogo.com/img/symbol/png/full_colored_light.png" width="40" title="Bash"/></a>&nbsp;
  <a href="https://www.php.net/"><img src="https://upload.wikimedia.org/wikipedia/commons/2/27/PHP-logo.svg" width="40" title="PHP"/></a>&nbsp;
  <a href="https://courses.missouristate.edu/kenvollmar/mars/download.htm"><img src="https://www.robertwinkler.com/projects/mips_book/images/mips_book.png" width="40" title="MIPS ASM"/></a>&nbsp;
  <a href="https://www.mathworks.com/"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" width="40" title="MATLAB"/></a>&nbsp;
  <a href="https://www.r-project.org/"><img src="https://www.r-project.org/logo/Rlogo.png" width="40" title="R"/></a>&nbsp;
  <a href="https://it.wikipedia.org/wiki/Fortran"><img src="https://cdn.icon-icons.com/icons2/2107/PNG/512/file_type_fortran_icon_130596.png" width="40" title="Fortran"/></a>&nbsp;
  <a href="https://www.arduino.cc/"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Arduino_Logo.svg/720px-Arduino_Logo.svg.png" width="40" title="Arduino"/></a>&nbsp;
  <!-- web -->
  <a href="https://www.w3.org/html/"><img src="https://cdn-icons-png.flaticon.com/512/732/732212.png" width="40" title="HTML5"/></a>&nbsp;
  <a href="https://www.w3schools.com/css/"><img src="https://www.geekandjob.com/uploads/wiki/31157387f2ac17b4f700bc4c4c9e8a66.png" width="40" title="CSS3"/></a>&nbsp;
  <a href="https://laravel.com/"><img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Laravel.svg" width="40" title="Laravel"/></a>&nbsp;
  <!-- data / math -->
  <a href="https://it.wikipedia.org/wiki/Structured_Query_Language"><img src="https://static.vecteezy.com/system/resources/thumbnails/036/044/336/small_2x/sql-database-icon-logo-design-ui-or-ux-app-png.png" width="55" title="SQL"/></a>&nbsp;
  <a href="https://www.mysql.com/products/workbench/"><img src="https://www.latex-project.org/about/logos/latex-project-logo_288x288.svg" width="40" title="LaTeX"/></a>&nbsp;
  <a href="https://scikit-learn.org/"><img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width="40" title="scikit-learn"/></a>&nbsp;
  <!-- editors -->
  <a href="https://code.visualstudio.com"><img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Visual_Studio_Code_1.35_icon.svg" width="40" title="VSCode"/></a>&nbsp;
  <a href="https://zed.dev/"><img src="https://zed.dev/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fstable-app-logo.9b5f959f.png&w=128&q=75" width="40" title="Zed"/></a>&nbsp;
  <a href="https://notepad-plus-plus.org/"><img src="https://freesvg.org/img/1661420472npp.png" width="40" title="Notepad++"/></a>&nbsp;
  <a href="https://github.com/tmux/tmux/wiki"><img src="https://cdn.worldvectorlogo.com/logos/tmux.svg" width="40" title="tmux"/></a>&nbsp;
  <!-- tools & platforms -->
  <a href="https://git-scm.com/"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" width="40" title="Git"/></a>&nbsp;
  <a href="https://learn.microsoft.com/it-it/windows/wsl/"><img src="https://store-images.s-microsoft.com/image/apps.61786.14131597032361940.38d2a067-3798-455f-934a-f69935156b3d.eb49d3ac-e311-4e6f-b89b-f1fe8db9d73b" width="40" title="WSL"/></a>&nbsp;
  <a href="https://www.putty.org/"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/PuTTY_Icon.svg/2048px-PuTTY_Icon.svg.png" width="40" title="PuTTY"/></a>&nbsp;
  <a href="https://www.teamviewer.com/it/"><img src="https://upload.wikimedia.org/wikipedia/commons/3/31/TeamViewer_Logo_Icon_Only.svg" width="40" title="TeamViewer"/></a>&nbsp;
  <a href="https://developer.android.com"><img src="https://developer.android.com/images/logos/android.svg" width="40" title="Android"/></a>
</p>

---

## `sole :: IO Research`

```haskell
sole :: IO Research
sole = do
  lab       <- joinLab "ACLAI"
  -- Applied Computational Logic and Artificial Intelligence
  -- Dept. of Mathematics and Computer Science, University of Ferrara
  framework <- develop "SOLE"
  -- SymbOlic LEarning framework
  return $ framework <> lab
```

> *"Currently working in the ACLAI Laboratory, focusing on the development*
> *of the SOLE (SymbOlic LEarning) framework."*

---

## `reach :: Channel -> Maybe Marco`

```haskell
reach :: Channel -> Maybe Marco
reach Email    = Just "perrottamarco2011@gmail.com"
reach LinkedIn = Just "linkedin.com/in/marco-perrotta-b159b6244"
reach Reddit   = Just "DarkAltruistic9560"
reach GitHub   = Just "Perro2110"
reach _        = Nothing
```

---

## `ghStats :: IO ()`

<p align="center">
  <a href="https://git.io/awesome-stats-card">
    <img src="https://awesome-github-stats.azurewebsites.net/user-stats/Perro2110" alt="GitHub Stats"/>
  </a>
</p>

---

<p align="center">
  <sub><code>-- EOF :: Marco.Perrotta</code></sub>
</p>
