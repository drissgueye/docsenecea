---
label: Référence
icon: book
order: 60
---

# Référence

## Statuts des requêtes

| Code | Libellé | Description |
|---|---|---|
| `SUBMITTED` | Soumise | Requête créée, non encore prise en charge |
| `UNDER_REVIEW` | En cours d'examen | Prise en charge par un agent |
| `PENDING_INFO` | En attente d'information | Complément demandé à l'adhérent |
| `IN_PROGRESS` | En traitement | Actions en cours |
| `RESOLVED` | Résolue | Traitement terminé, validation en attente |
| `CLOSED` | Clôturée | Requête terminée |
| `CANCELLED` | Annulée | Requête annulée par l'adhérent ou l'admin |

---

## Catégories par défaut

> Les catégories peuvent varier selon la configuration de votre syndicat.

- Conditions de travail
- Rémunération et salaires
- Congés et absences
- Santé et sécurité au travail
- Contrat et statut
- Formation professionnelle
- Discrimination et harcèlement
- Représentation syndicale
- Autre

---

## Niveaux de priorité

| Priorité | Délai cible de traitement |
|---|---|
| Basse | 15 jours ouvrés |
| Normale | 7 jours ouvrés |
| Haute | 3 jours ouvrés |
| Urgente | 24 heures |

---

## Limites techniques

| Paramètre | Valeur |
|---|---|
| Taille max. d'une pièce jointe | 10 Mo |
| Formats acceptés | PDF, JPG, PNG, DOCX, XLSX |
| Nombre max. de pièces jointes par requête | 5 |
| Longueur max. du titre | 100 caractères |
| Délai de contestation après résolution | 7 jours |

---

## Glossaire

**Adhérent** — Membre du syndicat inscrit sur le portail.

**Agent** — Membre du personnel syndical chargé du traitement des requêtes.

**Requête** — Demande ou signalement soumis par un adhérent via le portail.

**File d'attente** — Liste des requêtes non assignées ou en attente de traitement.

**Note interne** — Commentaire visible uniquement par les agents et administrateurs, non communiqué à l'adhérent.

**Clôture automatique** — Fermeture automatique d'une requête résolue si l'adhérent n'a pas contesté dans les 7 jours.

---

## Codes d'erreur fréquents

| Code | Message | Cause probable |
|---|---|---|
| `ERR_AUTH_001` | Session expirée | Reconnectez-vous |
| `ERR_FILE_001` | Fichier trop volumineux | Réduisez la taille du fichier |
| `ERR_FILE_002` | Format non supporté | Utilisez un format accepté |
| `ERR_FORM_001` | Champ(s) obligatoire(s) manquant(s) | Vérifiez le formulaire |
| `ERR_PERM_001` | Accès refusé | Votre rôle ne permet pas cette action |
