# git-hints

## Небольшой гит-репозиторий для самостоятельной работы

`git clone https://github.com/PraktikumJava/git-hints.git`

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "git commit"     --> tracked/comitted;
  tracked/comitted --> "Changing" --> modified;
  modified --> "git add" --> staged;
  staged --> "Changing" --> modified; 

``` 
