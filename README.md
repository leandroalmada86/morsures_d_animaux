# morsures_d_animaux

Le dataset

Le dataset Health Animal Bites (Santé - Morsures d'animaux) provient du recensement des plaintes des forces de l'odre suite à des morsures d'animaux. L'objectif de l'ensemble de données est de prédire de manière diagnostique quels animaux sont les plus susceptibles de mordre les humains, quels sont les facteurs les plus fortement associés à une identification positive de la rage, et si certaines races de chiens sont plus susceptibles de mordre que d'autre?. 

Attributs des incidents de morsure d'animaux signalés et étudiés par le département de la santé publique et du bien-être de Louisville Metro. Les données personnelles/identifiantes ont été supprimées.

Ci-dessous, le nom des colonnes :

columns={
    bite_date : La date à laquelle la morsure s'est produite
    SpeciesIDDesc : Espèce animale
    BreedIDDesc : Race (si connue)
    GenderIDDesc : Sexe (de l'animal)
    couleur : Couleur de l'animal
    vaccination_yrs : combien d'années se sont écoulées depuis la dernière vaccination
    date_vaccination : date de la dernière vaccination
    victim_zip : code postal de la victime
    AdvIssuedYNDesc : si un avis a été émis
    WhereBittenIDDesc : sur quelle partie du corps se trouve la morsure
    quarantaine_date : si l'animal a été mis en quarantaine
    DispositionIDDesc : si l'animal est sorti de quarantaine
    headsentdate : la date à laquelle la tête de l'animal a été envoyée au laboratoire
    release_date : la date à laquelle l'animal a été relâché
    ResultsIDDesc : résultats des tests de laboratoire (pour la rage)
}

Faux données:

columns={
    age : Age du animal
    adopted : Si l'animal était adopté ou pas
}

- étudier la probabilité que l'animal ait été adopté ou non influence les morsures

