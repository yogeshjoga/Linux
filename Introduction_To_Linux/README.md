# Introduction of linux
  linux is a OS, it's just kernel not a fully operation system file.
```bash
    Linux features
        Multiuser capablility
              - Admin (root/sudo-su)
              - Regular user
              - Service user
        It support's Multitasking 
                more then one method performed at a time
        Portability
        Security
        Live cd/usb 
            without installing OS we can run live in cd/usb
        its SUPPORTS GUI also now
        Support's cutomized keyboard
        Application supports
        File system
        open Source
        Linux have own language that is BASH SCRIPTING


     LINUX DISTROS
        - UBUNTU (its like apple mac Os)
        - FEDORA (RedHat based)
        - LINUX MINT(its like windows)
        - DEBIAN (for best usage hacking and security)
        - REDHAT LINUX ENTP (commerical)
        - CENTOS (RedHat withour trademark)
        - OPEN SUSE (fedora old)
        - ARCH LINUX(advance linux users)



```

## Intro part 2 a little commands for Default variable and custom variables setting
```bash
        Default variables
        # linux is a case sensitive we can follow this.
                - PATH
                - USER
                - HOME
                - ENV
                - UID
                - EDITOR
                - SHELL
            Ex: 
                    syntax: export variable_name=variable_value

                    export a=100 # Assining the variable and value ntg like we can declar and inti in java variable 
                    # we can call the variable by using $ dollar symbol

                    # for example is
                           export MyNameIs=yogesh # creating a variable
                           echo $yogesh # calling the variable

                    # How to remove the variable
                            unset $yogesh # unset is the keyword and yogesh is the variable name

                    # set and unset command, set with flag we can perform a new tasks 
                            set -X # debugging turn off
                            set +X # debugg trun on 
                            # we can write lot of commands like this now we dont want all commands
                    # export command
                    # export also same like set and unset command we can use inbuild flags
                    # for example you have one function/method to save system but you need to use every single hour
                    # what will you do again and again search function and run that
                    # we have one option in linux just export that function into local machine once
                    # you run n number of times its no need to live compiler it will excute at run time only

                    caseStudy:
                                # this is a simple function
                                function yogi(){
                                    echo "my name yogesh joga ";
                                }
                                # we can automat this function 
                            
                                export -f yogi # -f flag mean functio to export into local env variables


```
