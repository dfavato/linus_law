# Linus's Law: More Eyes Fewer Flaws in Open Source Projects

Danilo Favato, Daniel Ishitani, Johnatan Oliveira, Eduardo Figueiredo

Department of Computer Science, Federal University of Minas Gerais (UFMG)

Belo Horizonte, Brazil

## Organization
Research data and methodology used in the paper "Linus's Law: More Eyes Fewer Flaws in Open Source Projects" to be presented in the SBQS 2019.

The study was organized in two parts:

- Pilot study
- Main study

Sampling methodology used in the Main study is in the Python Notebook named 'Main study/Sampling'.

Statistical analysis of both studies is in the R Notebook named 'Statistical\_Analysis.nb.html'.

Source code of all projects analyzed in the Main study is in 'Main Study/projects\_source\_code.tar.7z.part\*'. The files were compressed to save space but had to be divided in order to comply with github max file size policy.

To extract the files issue the following commands:

```
cd Main\ study
cat projects_source_code.tar.7z.parta* > projects_source_code.tar.7z
7z x -so projects_source_code.tar.7z | tar xf - -C .
```
