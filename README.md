# Dépôt de documents

Espace de partage de documents sur invitation, avec dossiers, sous-dossiers, grades (Visiteur, Intervenant, Travailleur) et droits d'accès.

Page unique (`index.html`) qui s'appuie sur [Supabase](https://supabase.com) pour les comptes, la base et le stockage des fichiers. Les droits sont vérifiés côté base (Row Level Security) : la clé présente dans la page est la clé publique.
