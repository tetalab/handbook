Astuces basiques
==========

Tout comme avec d'autres formes de communication sur le web, vous devriez toujours prendre quelques précautions afin de vous assurer les meilleures chances de protéger votre vie privée

En bref : 
---------

 * Les mots de passe ne devraient pas avoir de rapport avec des détails personnels et devraient contenir un mélange de plus de 8 lettres et autres caractères.
 * Assurez-vous toujours que votre connexion est sécurisée lorsque vous lisez vos mails sur un réseau sans-fil, spécialement dans les cyber-cafés.
 * Les fichiers temporaires (le "cache") sur l'ordinateur que vous utilisez pour lire vos e-mails peuvent présenter un risque. Supprimez-les fréquemment.
 * Créez et maintenez séparés des comptes e-mail en fonction de vos intérêts.
 * Chiffrez tout message que vous n'oseriez pas écrire sur une carte postale. 
 * Soyez conscient des risques d'avoir vos mails hébergés par une entreprise ou une organisation.

Mots de passe
---------

Les mots de passe sont le premier point de vulnérabilité dans la communication par e-mail. Même un mot de passe sûr peut être lu lors d'une transmission, sauf si la connexion est sûre (voir TLS/SSL dans le glossaire). De plus, ce n'est pas parce qu'un mot de passe est long qu'il ne peut être deviné en utilisant des connaissances sur vous et votre vie pour déterminer les mots et les nombres correspondants.

La règle générale pour créer des mots de passe est qu'ils doivent être longs (8 caractères ou plus) et contenir un mélange de lettres et autres caractères (chiffres et symboles, ce qui signifie que vous devriez choisir un mot court). Combiner votre date de naissance avec un nom de famille est un bon exemple de ce qu'il ne faut pas faire. Ce genre d'information est facile à trouver en utilisant des données publiques. Une astuce répandue consiste à baser le mot de passe sur une phrase favorite et, pour perturber les gens, la saupoudrer de quelques chiffres. Le mieux étant d'utiliser un générateur de mots de passe, soit sur votre machine, soit en ligne.

Il est souvent difficile de se souvenir de tels mots de passe et une seconde vulnérabilité apparait : la découverte physique. Sachant qu'il n'y a pas de meilleur moyen de stocker un mot de passe que votre cerveau, des services comme OnlinePasswordGenerator ([http://www.onlinepasswordgenerator.com/](http://www.onlinepasswordgenerator.com/)) offrent un bon compromis en générant aléatoirement des mots de passe qui ressemblent vaguement à des mots existants et en vous offrant une liste dans laquelle piocher.

Si vous choisissez de stocker votre mot de passe hors de votre tête, vous avez le choix de l'écrire ou d'utiliser un logiciel de gestion de mots de passe. Ce qui peut être une décision risquée si le compte mail et son mot de passe sont sur un même appareil comme votre téléphone ou votre ordinateur. 

Un logiciel de gestion de mot de passe, comme KeePass, entrepose vos divers mots de passe et phrases secrètes en un endroit et les rend accessible via un mot de passe ou une phrase secrète principale. Ceci impose une forte pression sur le mot de passe principal. Si vous décidez d'utiliser un tel logiciel, rappelez-vous d'utiliser un mot de passe sûr.

Au final, vous devriez utiliser des mots de passe différents pour vos divers comptes. De cette façon, si l'un d'eux est piraté, vos autres comptes resteront en sécurité. N'utilisez jamais le même mot de passe au travail et pour vos comptes e-mail personnels. Voir la section **Mots de passe** pour en savoir plus sur les façons de vous sécuriser.

Lire des e-mails dans des lieux publics
------------------------------

Un des grands conforts des réseaux sans-fil et du "Cloud computing" est la possibilité de travailler n'importe où. Vous pouvez régulièrement vouloir consulter vos e-mails dans des cyber-cafés ou des lieux-publics. Espions, criminels et individus douteux sont connus pour visiter régulièrement ces endroits afin de profiter de riches opportunités offertes pour le vol d'identité, l'espionnage d'e-mails ou le piratage de comptes bancaires.

Nous nous trouvons souvent au centre d'un risque sous-estimé de quelqu'un écoutant vos conversations en utilisant l'analyse de paquets. Cela pose problème que le réseau lui-même soit ouvert ou protégé par un mot de passe. Si quelqu'un rejoint le même réseau chiffré, il (elle) peut aisément capturer et lire tout le trafic *non-sécurisé* (voir le chapitre **Connexion Sécurisée**) de tous les utilisateurs du même réseau. Une carte wifi peut être achetée pour une bouchée de pain et donnent à ceux qui savent comment capturer et analyser des paquets réseau la possibilité de lire votre mot de passe pendant que vous lisez vos e-mails.

Voici une simple règle qui s'applique tout le temps : si le cyber-café offre une connexion filaire, utilisez-la ! Enfin, tout comme devant un distributeur de billets, assurez-vous que personne ne regarde par-dessus votre épaule lorsque vous tapez votre mot de passe.


Cache Cunning
-------------

Here again convenience quickly paves the road to bad places. Due to the general annoyance of having to type in your password over and over again, you ask the browser or local mail client to store it for you. This is not bad in itself, but when a laptop or phone gets stolen, it enables the thief to access the owner's email account(s). The best practice is to clear this cache every time you close your browser. All popular browsers have an option to clear this cache on exit. 

One basic precaution can justify you holding onto your convenient cache: disk encryption. If your laptop is stolen and the thief reboots the machine, they'll be met with an encrypted disk. It is also wise to have a screen lock installed on your computer or phone. If the machine is taken from you while still running your existing browsing session, it cannot be accessed.
Securing your communication

Whenever you write and send email in a browser or use an email program (Outlook Express, Mozilla Thunderbird, Mail.app or Mutt), you should always ensure to use encryption for the entire session. This is easily done due to the popular use of *TLS/SSL (Secure Socket Layer)* connections by email servers (See glossary **TLS/SSL**).

If using a browser to check your email, check to see if the mail server supports SSL sessions by looking for https:// at the beginning of the URL. If not, be sure to turn it on in your email account settings, such as Gmail or Hotmail.This ensures that not just the login part of your email session is encrypted but also the writing and sending of emails.

At the time of writing, Google's Gmail uses TLS/SSL by default whereas Hotmail does not. If your email service does not appear to provide TLS/SSL, then it is advised to stop using it. Even if your emails are not important, you might find yourself 'locked out' of your account one day with a changed password!

When using an email program to check your email, be sure that you are using TLS/SSL in the program options. For instance in Mozilla Thunderbird the option for securing your outgoing email is found in `Tools -> Account Settings -> Outgoing Server (SMTP)` and for incoming email in `Tools -> Account Settings -> Server Settings`. This ensures that the downloading and sending of email is encrypted, making it very difficult for someone on your network, or on any of the networks between you and the server, to read or log your email.
Encrypting the email itself

Even if the line itself is encrypted using a system such as SSL, the email service provider still has full access to the email because they own and have full access to the storage device where you host your email. If you want to use a web service and be sure that your provider cannot read your messages, then you'll need to use something like *GPG* (Appendix for **GnuPG**) with which you can encrypt the email. The header of the email however will still contain the IP (Internet address) that the email was sent from alongside other compromising details. Worth mentioning here is that the use of *GPG* in webmail is not as comfortable as with a locally installed mail client, such as *Thunderbird* or *Outlook Express*.

Account Separation
------------------

Due to the convenience of services like Gmail, it is increasingly typical for people to have only one email account. This considerably centralises the potential damage done by a compromised account. More so, there is nothing to stop a disgruntled Google employee from deleting or stealing your email, let alone Google itself getting hacked. Hacks happen.

A practical strategy is to keep your personal email, well, personal. If you have a work email then create a new account if your employers haven't already done it for you. The same should go for any clubs or organisations you belong to, each with a unique password. Not only does this improve security, by reducing the risk of whole identity theft, but greatly reduces the likelihood of spam dominating your daily email.

A note about hosted email
-------------------------

Those that provide you with the service to host, send, download and read email are not encumbered by the use of TLS/SSL. As hosts, they can read and log your email in plain text. They can comply with requests by local law enforcement agencies who wish to access email. They may also study your email for patterns, keywords or signs of sentiment for or against brands, ideologies or political groups. It is important to read the EULA (End-user license agreement) of your email service provider and do some background research on their affiliations and interests before choosing what kind of email content they have access to. These concerns also apply to the hosts of your messages' recipients.
