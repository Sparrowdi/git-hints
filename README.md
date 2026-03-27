# git-hints

## Небольшой гит-репозиторий для самостоятельной работы

`git clone https://github.com/PraktikumJava/git-hints.git`

```mermaid
graph TD;
  untracked -- "git add" --> staged;
  modified -- "git add" --> staged;
  staged    -- "git commit"     --> tracked/comitted;
  tracked/comitted -- "Изменения" --> modified;
  staged -- "Изменения" --> modified; 

``` 
