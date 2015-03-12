This is a programming library for Agda. This means that it contains almost no
proofs and it is not afraid to turn off the termination checker if it gets in
the way. If you are looking to formalize mathematics, this library is not for
you, but if you want to write programs in Agda this might just be what you are
looking for.

Note that this library is not compatible with the Agda standard library at
https://github.com/agda/agda-stdlib.

-------------------------------------------------------------------------------
## Git commands to keep fork up-to-date with upstream repo

    git remote add upstream git@github.com:UlfNorell/agda-prelude.git
    git fetch upstream
    git merge upstream/master
    git push origin master

