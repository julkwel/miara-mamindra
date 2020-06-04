# First-contribution-setup
Ho fanampiana ireo rehetra izay vao hi-contribuer amin'ny projet OpenSource.

Rehefa hi-contribuer amin'ny projet iray ianao dia :

1 - Manova fork an'ilay projet.

2 - Mandehana ao amin'ny repository anao dia ho hitanao ao ilay projet nataonao fork.

3 - Cloneo ilay projet noforkenao ao amin'ny repository anao
```
$ git clone ilay_url_ao_amin_repo_anao
```
4 - Midira ao amin'ilay projet en local anao rehefa vo-clone ilay izy.
```
$ cd ilay_repo
```
5 - Apetraho ao amin'ilay repos local anao ilay url an'ilay projet source mba ho à jour foana ny local anao
```
$ git remote add upstream ilay_url_original_an_ilay_projet_noforkena
```
6 - Raiso ny modification rehetra any amin'ny upstream
```
$ git fetch upstream
```
7 - Mergeo ao amin'ilay master en local anao ilay upstream raha misy modification
```
$ git merge upstream/master
```
8 - Mi-creeva branche hafa raha hanampy zavatra na hanohy hiasa ao amin'ilay projet ianao

```
$ git checkout -b "brancheko_vaovao"
```
____
9 - Ataovy ny installation rehetra, rehefa misy tsy mety dia anontanio ny maintainer (tompony) an'ilay projet.
```
$ node, composer ...
```

Rehefa izay dia tohizanao ny zavatra ataoanao ao amin'ny local anao , rehefa afa-po ianao ao amin'ny local ianao dia pushenao ny modification nataonao , alohan'ny i-pushena anefa dia manaova fetch an'ilay upstream foana aloha ( satria mety ho betsaka ny contributeur ary misy mikitika foana ilay repo ).
Raha misy modif dia manao merge indray .
```
$ git fetch upstream
```
Raha misy modif dia mergeo ao amin'ny master anao:
```
$ git merge upstream/brancheko_vaovao
```

Rehefa izay dia akaro amin'izay ilay modif anao:
```
$ git add fichier_no_modifier_nao
$ git commit -m "message commit anao"
$ git push -u origin brancheko_vaovao
```

Vita izay dia manaova pull request avy amin'ilay branche no-creenao.

Misaotra anao namaky 😉


*Happy coding !!!*
