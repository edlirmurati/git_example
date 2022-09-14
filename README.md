# git_example

hello commit

## what are the benefits of commits?

1. Mit Commits kann man seine Entwicklung anschauen und dann dementsprechend nachvollziehen. Es ist ebenfalls eins der Hauptfunktionen.

## Is there another way to verify a commit was created?

2. Mit dem Command "git log" stellt man fest, ob ein commit erstellt wurde oder nicht.

## How to check if a file is tracked and if not, then track it?****


3. Mit Status checket man ob ein File getracked wurde. Wenn Git nicht anwtortet, wurde das File noch nie getracked. Falls es schonmal getracked worden ist, antwortet Git mit dem File. Man sollte sie tracken da dann ein Snapshot erstellt wird und es somit gespeichert ist.

* this
* is 
* a
* bulleted
* list


## In which situation should you use `git diff`?
Ich benutze "git diff" wenn ich Git Datenquellen miteinander vergleichen will.

## How do you create a patch with `git diff`?
Schritt Eins ist: Den Patch "git diff > some-changes.patch" erstellen.
Schritt Zwei ist: Diesen Patch auf den Computer kopieren und anschliessend dann "git apply /path/to/some-changes.patch" in das Git Bash eingeben. Und nun befinden sich die Änderungen in der Kopie.