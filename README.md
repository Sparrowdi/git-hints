# git-hints

## Небольшой гит-репозиторий для самостоятельной работы

`git clone https://github.com/PraktikumJava/git-hints.git`

```mermaid
graph TD;
  untracked -- "git add" --> staged;
  staged    -- "git commit"     --> tracked/comitted;
  modified --> "git add" --> staged;

``` 
