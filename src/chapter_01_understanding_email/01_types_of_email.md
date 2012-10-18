Les types d'e-mail
==============

L'utilisation de messagerie électronique se présente toujours sous 2 formes :

 * Les e-mails lus, écrits et envoyés via le *navigateur* (webmail), ou

 * Les e-mails lus, écrits et envoyés via un *client mail*, comme Mozilla Thunderbird, Mail.app ou Outlook Express


E-mails hébergés à distance (webmail), accédés via un navigateur web.
----------------------------------------------------------------

Les services de messagerie accessibles uniquement avec un *navigateur*, aussi appelés webmail, impliquent généralement un compte chez un fournisseur distant comme Google (GMail), Microsoft (Hotmail) ou Yahoo (Yahoo Mail). Les opportunités commerciales offertes par l'hébergement des mails de tiers sont multiples : synergie avec les autres services offerts par la compagnie, mise en valeur de la marque et, plus important, analyse de vos mails pour des signes utilisables pour évaluer vos interêts -- quelque chose d'une grande valeur pour l'industrie publicitaire (en plus de certains gouvernements).

E-mails hébergés à distance (webmail), accédés via un client mail ou un navigateur
------------------------------------------------------------------------------

L'utilisation d'un programme comme Outlook, Thunderbird, Mail.app peut aussi fonctionner avec un service de webmail comme celui de GMail ou de votre entreprise. Dans ce cas, les e-mails peuvent toujours être téléchargés sur votre ordinateur mais continuent d'exister sur le serveur de mail (ex. Gmail). De cette façon, accéder aux e-mails ne nécessite plus de navigateur, mais vous continuer d'utiliser le service de Gmail ou Hotmail. La différence entre le stockage de vos e-mails sur votre ordinateur avec un client mail et le stockage sur un serveur distant (Gmail, Hotmail, ou le service de mail fourni par votre Université) sur Internet peut apparaitre troublante au premier abord.


E-mails envoyés et reçus via un client mail, non stockés sur une machine distante
-----------------------------------------------------------------------------

Finalement, des e-mails peuvent aussi être envoyés vers un serveur mais ne pas y être stockés, à peine relayés vers leur destination dès que le mail atteint le serveur de relais. Google et Microsoft n'autorisent pas ce type de fonctionnement. C'est plutôt votre université ou votre entreprise qui vous permettra ce fonctionnement. Gardez à l'esprit que cela n'élimine pas le risque d'un administrateur du système qui copierait discrètement les e-mails lors de leur transit par le serveur.

Generally, using webmail alongside downloading it using an email program is the best approach. This approach adds redundancy (local backups) alongside the option to delete all email from the remote server once downloaded. The latter option is ideal for content sensitive information where the possibility of account hijacking is high but risks total loss of email should the local machine go missing, without backups. Secondly, when using an email program, we have the option of using Email Encryption such as the popular GPG, something not easily set up and used with browser-only webmail services. In any case, disk encryption on the local machine is highly advisable (Appendix **Disk Encryption**).

Context considerations
----------------------

You may be a server administrator yourself and run your own email service. Or your email could be stored on your company or bosses' server. Finally you may be using a service provided by a corporation, like Google (Gmail) or Microsoft (Hotmail). Each comes with its own interesting mix of considerations that relates precisely to the basic fact that unless the email itself is encrypted, the administrator of the email server can still secretly copy the email the moment it reaches the server. It doesn't matter that you may be using *TLS/SSL* (Appendix **SSL**) to login and check your email as this only protects the connection between your local machine and the server.

As always, if you know the risks and feel concerned it is wise to listen to them - don't send sensitive email using a service you don't trust.
Employer/Organisation

Your employer or an organisation that you are involved with is in a very good position to take advantage of your trust and read the emails of your business email account that is stored on their email server, perhaps in an effort to learn about you, your motivations, agendas and interests. Such cases of employer->employee spying are so typical they do not bear mention. Your only measure against it is to use an email encryption solution like GPG (Appendix GPG).

Self-administered email server
------------------------------

Generally speaking this is the ideal hosting configuration, but requires a higher level of technical skill. Here, in general, the risks to privacy are not only in protecting your own email against attempts at exploit (poor passwords, no SSL) but in that you have a responsibility, and perhaps a temptation, to read the emails of those you provide a service for.

'Free' email services
---------------------

As mentioned above the risks of storing and sending your email using a service provided by a corporation are rather high if respect of your civil right to privacy is valued. The companies hosting your love letters, random expressions and diaries are always at risk of yielding to pressures from political, economic and law enforcement interests of the country to which they are legally subject. A Malaysian Gmail user, for instance, risks exposing her interests and intents to a government she did not elect, not to mention business partners of Google interested in expanding their market reach.

Non-profit
----------

Several non-profit web hosts offer free email accounts to organisations that are themselves non-profit or philanthropic. Some of them even offer wikis, mailing lists, chats and social networks. A consideration for organisations working in a political field may be differences of interests between the state in which the email is hosted and the political interests of the organisation using that service. Such risks would ideally be reflected in the End User License Agreement.

Notes on email forwarding
-------------------------

Email forwarding services provide the great convenience of 'linking' one email account to another as the user sees fit. This of course is most commonly used when an account holder is on holiday and would like email forwarded from their work account to another used during travel or otherwise inaccessible outside the workplace. The risk with any external email forwarding service is the same as with remotely hosted emails through Gmail for instance: it can be copied and stored. Here email encryption using a system such as *GPG* (Appendix **GPG**) will ensure that if it is copied at least it cannot be read.
