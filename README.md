# 42 Québec Cursus - ft_printf

<br />
<div align="center">
	<a href="https://github.com/yanislabbe">
	<img src="images/success.png" alt="success" width="100" height="100">
	</a>
</div>


### À propos

Vous devez implémenter la fonction printf() de la libc.

### Partie obligatoire

Le protoype de ft_printf devra être :
	int	ft_printf(const char *, ...);

Voici quelques impératifs à respecter :

- Contrairement à la fonction printf() originale, vous ne devez pas gérer de buffer.
- Vous devez gérer les conversions suivantes : cspdiuxX%
- Votre rendu sera comparé à la fonction printf() originale.
- Vous devez utiliser la commande ar pour créer votre bibliothèque. L'utilisation de la commande libtool est interdite.
- Votre libftprintf.a doit être créé à la racine de votre dépôt.

Vous devez implémenter les conversions suivantes :

- %c : Affiche un seul caractère.
- %s : Affiche une chaîne de caractère (telle que définie par la convention C).
- %p : L'argument de pointeur void * doit être affiché en hexadécimal.
- %d : Affiche un nombre décimal (base 10).
- %i : Affiche un entier en base 10.
- %u : Affiche un nombre décimal non signé (base 10).
- %x : Affiche un nombre en hexadécimal (base 16) avec des lettres minuscules.
- %X : Affiche un nombre en hexadécimal (base 16) avec des lettres majuscules.
- %% : Affiche un signe pourcentage.

## Auteur

- Yanis Labbé#
