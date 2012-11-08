Craintes
=====
*Qui peut lire les mails que j'ai déjà reçus ou envoyés ?*

*Qui peut lire les mails que j'envoie lors de leur transit sur Internet ?*

*Est-ce que les personnes à qui j'envoie des mails peuvent les partager avec d'autres personnes ?*

Les e-mails envoyés "en clair" sans aucun chiffrment (ce qui signifie la grande majorité des e-mails échangés aujourd'hui) peuvent être lus, journalisés et indexés par n'importe quel serveur ou routeur situé le long du trajet du message entre l'emetteur et le récepteur. Admettons que vous utilisiez une connexion chiffrée (voir le glossaire pour SSL/TLS) entre vos appareils et votre fournisseur de messagerie (ce que tout le monde devrait faire), cela signifie en pratique que les personnes suivantes peuvent encore lire n'importe quel message :
 
 1. Vous
 2. Votre fournisseur de messagerie
 3. Les opérateurs et propriétaires de n'importe quelle connexion réseau intermédiaire (souvent des conglomérats internationaux ambigüs ou des états souverains)
 4. Le fournisseur de messagerie du destinataire
 5. Le destinataire désigné

De nombreux founisseurs de messagerie (comme GMail) inspectent tous les messages envoyés et reçus par leurs utilisateurs dans le but d'afficher de la publicité ciblée. Si cela peut être un compromis raisonnable pour la plupart des utilisateurs la majorité du temps (messagerie gratuite !), il est dérangeant pour beaucoup que même la plus privée de leur communication soit inspectée et indexée comme un morceau d'un profil caché et potentiellement très intrusif maintenu par un géant commercial tout-puissant avec un dessein lucratif.

De plus, quelqu'un pouvant légalement faire pression sur les groupes ci-dessus pourrait requérir ou demander :
Additionally, somebody who can legally pressure the groups above could request or demand:

 1. des méta-données journalisées sur les e-mails (listes des messages envoyés ou reçus par un utilisateur, sujets, destinataires) dans certaines juridictions même sans mandat.
 2. les messages envoyés et reçus par un utilisateur ou un groupe spécifiques, avec un mandat ou un ordre du tribunal dans certaines juridictions.
 3. une connexion dédiée pour siphonner *tous* le trafic et les messages afin de les analyser hors-site.

Dans le cas où un utilisateur a une relation professionnelle ou de service avec son fournisseur d'e-mails, la plupart des gouvernements défendront les droits de la vie privée de l'utilisateur contre la lecture et le partage non-autorisé de messages, bien que ce soit souvent le gouvernement lui-même qui recherche des informations, et que les usagers acceptent fréquemment de renoncer à certains droits dans leur contrat de service. Cependant, quand le fournisseur de messagerie est l'employeur de l'usager ou une institution académique, les droits à la vie privée ne s'appliquent pas. Enfonction de la juridiction, les entreprises ont généralement légalement le droit de lire tous les messages envoyés et reçus par leurs employés, même les messages personnels envoyés en dehors de sheures de travail ou durant les congés. 

Histriquement, il était possible de s'en sortir avec des messages envoyés en texte clair parce que le cout de stockage et d'indexation du volume grandissant de mails était trop élevé : il était déjà copliqué d'acheminer les e-mails de façon fiable. Voici pourquoi beaucoup de systèmes de messagerie ne contiennent pas de mécanismes pour préserver la confidentialité de leur contenu. Maintenant que le coût de monitoring a chuté plus rapidement que la croissance du trafic Internet on peut envisager un monitoring à grande échelle et l'indexation de tous les messages (tant du côté émetteur que récepteur) même pour les utilisateurs et messages les plus anodins.[CITE:corporate email archiving/spying, blue coat, Syrian monitoring, USA Utah data center, USA intercept scandals]

For more about legal protections of email messages "at rest" (technical term for messages stored on a server after having been delivered), especially regarding government access to your email messages, see:

 * https://ssd.eff.org/3rdparties/govt/stronger-protection (USA)
 * http://en.wikipedia.org/wiki/Data_Protection_Directive (EU)

Just like there are certain photos, letters, and credentials that you would not post "in the clear" on the Internet because you would not want that information to get indexed accidentally and show up in search results, you should never send email messages in the clear that you would not want an employer or disgruntled airport security officer to have easy access to.

Random abuse and theft by malicious hackers
-------------------------------------------

*What if somebody gets complete control of my email account?*

*I logged in from an insecure location... how do I know now if my account has been hacked?*

*I've done nothing wrong... what do I have to hide?*

*Why would anybody care about me?*

Unfortunately, there are many practical, social, and economic incentives for malicious hackers to break into the accounts of random Internet individuals. The most obvious incentive is identity and financial theft, when the attacker may be trying to get access to credit card numbers, shopping site credentials, or banking information to steal money. A hacker has no way to know ahead of time which users might be better targets than others, so they just try to break into all accounts, even if the user doesn't have anything to take or is careful not to expose his information.

Less obvious are attacks to gain access to valid and trusted user accounts to collect contact email addresses from and then distribute mass spam, or to gain access to particular services tied to an email account, or to use as a "stepping stone" in sophisticated social engineering attacks. For example, once in control of your account a hacker could rapidly send emails to your associates or co-workers requesting emergency access to more secured computer systems.

A final unexpected problem affecting even low-profile email users, is the mass hijacking of accounts on large service providers, when hackers gain access to the hosting infrastructure itself and extract passwords and private information in large chunks, then sell or publish lists of login information in online markets.

Targeted abuse, harassment, and spying
--------------------------------------

*Something I wrote infuriated a person in power... how do I protect myself?*

If you find yourself the individual target of attention from powerful organizations, governments, or determined individuals, then the same techniques and principles will apply to keeping your email safe and private, but additional care must be taken to protect against hackers who might use sophisticated techniques to undermine your devices and accounts. If a hacker gains control of any of your computing devices or gets access to any of your email accounts, they will likely gain immediate access both to all of your correspondence, and to any external services linked to your email account.

Efforts to protect against such attacks can quickly escalate into a battle of wills and resources, but a few basic guidelines can go a long way. Use specific devices for specific communication tasks, and use them only for those tasks. Log out and shutdown your devices immediately when you are done using them. It is best to use open software encryption tools, web browsers, and operating systems as they can be publicly reviewed for security problems and keep up to date with security fixes.

*Be wary of opening PDF files using Adobe Reader or other proprietary PDF readers.* Closed source PDF readers have been known to be used to execute malign code embedded in the PDF body. If you receive a .pdf as an attachment you should first consider if you know the supposed sender and if you are expecting a document from them. Secondly, you can use PDF readers which have been tested for known vulnerabilities and do not execute code via java script. 

Linux: Evince, Sumatra PDF

OS X: Preview

Windows: Evince

Use short-term anonymous throw away accounts with randomly generated passwords whenever possible.

When Encryption Goes Wrong
--------------------------

*What happens if I lose my "keys"? Do I lose my email?*

Rigorous GPG encryption of email is not without its own problems.

If you store your email encrypted and lose all copies of your private key, you will be absolutely unable to read the old stored emails, and if you do not have a copy of your revocation certificate for the private key it could be difficult to prove that any new key you generate is truly the valid one, at least until the original private key expires.

If you sign a message with your private key, you will have great difficulty convincing anybody that you did not sign if the recipient of the message ever reveals the message and signature publicly. The term for this is *non-repudiation*: any message you send signed is excellent evidence in court. Relatedly, if your private key is ever compromised, it could be used to read all encrypted messages ever sent to you using your public key: the messages may be safe when they are in transit and just when they are received, but any copies are a liability and a gamble that the private key will never be revealed. In particular, even if you destroy every message just after reading it, anybody who snooped the message on the wire would keep a copy and attempt to decrypt it later if they obtained the private key.

The solution is to use a messaging protocol that provides *perfect forward secrecy* by generating a new unique session key for every conversation of exchange of messages in a random way such that the session keys could not be re-generated after the fact even if the private keys were known. The OTR chat protocol provides perfect forward secrecy ([http://en.wikipedia.org/wiki/Perfect_forward_secrecy](http://en.wikipedia.org/wiki/Perfect_forward_secrecy)) for real time instant messaging, and the SSH protocol provides it for remote shell connections, but there is no equivalent system for email at this time. 

It can be difficult to balance the convenience of mobile access to your private keys with the fact that mobile devices are much more likely to be lost, stolen, or inspected and exploited than stationary machines. An emergency or unexpected time of need might be exactly the moment when you would most want to send a confidential message or a signed message to verify your identity, but these are also the moments when you might be without access to your private keys if your mobile device was seized or not loaded with all your keys.
