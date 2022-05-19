# CFUtils

### Integrate dev version with another project
Write this at the beginning of the python script:  
    `import sys`   
    `sys_path=set(sys.path)`   
    `sys_path.add('D://ferreyra//cflab//cfutils')`  
    `sys.path=sys_path`

Then, import some module using my_package.my_module
