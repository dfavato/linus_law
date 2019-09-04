# Linus's Law: More Eyes Fewer Flaws in Open Source Projects

Danilo Favato, Daniel Ishitani, Johnatan Oliveira, Eduardo Figueiredo

Department of Computer Science, Federal University of Minas Gerais (UFMG)

Belo Horizonte, Brazil

## Organization
Research data and methodology used in the original paper "Linus's Law: More Eyes Fewer Flaws in Open Source Projects" to be presented in the SBQS 2019.

The study was organized in two parts:

- Pilot study
- Main study

Sampling methodology used in the Main study is in the Python Notebook named [Main study/Sampling.ipynb](https://github.com/dfavato/linus_law/blob/master/Main%20study/Sampling.ipynb).

Statistical analysis of both studies is in the R Notebook named [Statistical\_Analysis.nb.html](http://htmlpreview.github.io/?https://github.com/dfavato/linus_law/blob/master/Statistical_Analysis.nb.html).

Source code of all projects analyzed in the Main and Pilot study are inside their folders named as 'projects\_source\_code.tar.7z.part\*'. The files were compressed to save space but had to be divided in order to comply with github max file size policy.

To extract the files issue the following commands:

```
cd Main\ study
cat projects_source_code.tar.7z.part* > projects_source_code.tar.7z
7z x -so projects_source_code.tar.7z | tar xf - -C .

cd ../Pilot\ study
cat projects_source_code.tar.7z.part* > projects_source_code.tar.7z
7z x -so projects_source_code.tar.7z | tar xf - -C .
```

Inside the Pilot Study folder are also the configuration file used in PMD `smells_ruleset.xml` and the script used to extract the contributors from the git history of each project `git-score`.

