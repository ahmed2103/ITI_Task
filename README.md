To remove branches loaclly we use >>>>>> git branch -d branch_name
To remove them remotely we use >>>>>>>>> git push origin :branch_name

__________________________________________________________________________________________________________________________________________________________________________
                                           |
    Annotated tag                          |    lightweight Tag                   |
    _______________________________________|______________________________________|
    stored as full git object              |  only name point to the tag          |
                                           |                                      |
    contain meta data like:-               |  no meta data                        |
        tagger name                        |                                      |
        e-mail                             |  CMD:                                |
        date                               |      git tag v1.0                    |
        tag message                        |                                      |
                                           |                                      |
    CMD:                                   |                                      |
        git tag a v1.7 -m "msg for release"|                                      |
__________________________________________________________________________________|

___________________________________________________________________________________________________________________________________________________________________________

    Q: When to use rebase?
    
    1- when we want more clear history of commit as merge only git the the latest commit
    2- we dont want to pollute the other branch to with merge commit
    3- It is best to do it if we dont share the branch
    4- to combine multible commit into one
    
__________________________________________________________________________________________________________________________________________________________________________

    Q: How to List tags?
    
    CMD:
        git tag
__________________________________________________________________________________________________________________________________________________________________________

    Q: How to delete tag locally and remotely?

    Localy CMD:
                git tag -d v1.7
    
    remotely CMD:
                
                git push origin --delete v1.7
___________________________________________________________________________________________________________________________________________________________________________

    Q: How to add image?

    ![Ahmed Hasona](https://drive.google.com/uc?export=view&id=1Gc_vFrtEzNc9tpKkNK0CeOTeZN7ZvLrX)
