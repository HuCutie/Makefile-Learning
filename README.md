# Makefile-Learning  

## Chapter 0 Getting Started  
**1. Syntax**  
targets: prerequisites  
   command  
   command  
   command  

**2. Comment**  
Using ` # ` in an indepennt line as the comment symbol.  

**3. Variables**  
Variables can only be strings.  
Reference variables using `\$() ` or `\${} `.

## Chapter 1 Targets
**1. All target**  
Using all target to run multiple targets.  

**2. Multiple targets**  
When there are multiple targets for one rule, the commands will run for each target.  
`$@ ` is an automatic variable that contains the target name.  

## Chapter 2 Automatic Variables and Wildcards  
**1. Automatic variables**  
`$@ ` represents the file name.  
`$? ` represents the prerequisites newer than the target.  
`$< ` represents first target.  
`$^ ` represents all targets.  
`$% ` represents the target member.  