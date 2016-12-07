    mkdir hitobito_generic_composition
    cd hitobito_generic_composition
    git init
    HITOBITO_TAG=v1.13.1
    GENERIC_TAG=v1.13
    git submodule add https://github.com/hitobito/hitobito
    git submodule add https://github.com/hitobito/hitobito_generic
    cd hitobito
    git checkout $HITOBITO_TAG
    cd ..
    cd hitobito_generic
    git checkout $GENERIC_TAG
    cd ..
