# Parsing et croisement d'amendements déposés au parlement

Ce notebook implémente plusieurs éléments utiles pour travailler sur les amendmeents de loi, déposés à l'Assemblée Nationale ou au Sénat :
- lecture de liasse d'amendement (classe 'Amendement' et classe 'Liasse' qui correspond à un ensemble d'Amendement) utile pour parser automatiquement des amendements à partir de fichiers txt.
- Une fonction de matching pour retrouver les amendements similaires d'une liasse à l'autre. La difficulté vient du fait que d'une liasse à l'autre les amendements peuvent être modifiés et qu'ils changement de numérotation.

Cela s'avère utile notamment lors du travail sur la loi pour retrouver le travail déjà effectué sur la version précédente des amendements.
