I find that it's easier to organise this README in a
"question-answer" format. Questions are marked with "Q:", and answers
with "A:".

Q: Who are you?
A: I am Alexander Arkhipov, a Unix hacker from Moscow.

Q: How can I contact you?
A: finger arkhipov@alearx.org | grep -o 'Login: [^ ]*' |
   sed 's/Login: \(.*\)/\1@alearx.org/'

   You can use the output for both finger(1) and mail.

Q: Do you have a PGP key?
A: Yes, it's at ftp://alearx.org/pub/pgp/ -- pick the latest one.
   The pub directory is also mirrored on http and gopher.

Q: What services does alearx.org provide?
A: Most services are at alearx.org. There is a mail server running,
   so you can send me mail to this server. I publish news via finger
   and you can read them via http and gopher as well. I publish some
   files to the ftp server, and the pub directory is mirrored to http
   and gopher. There are the http and gopher sites, which are mostly
   identical. You can clone my git repositories via anongit (see the
   /git/ directory on either www or gopher site). I also maintain a
   boring site with a blog and a resume at pro.alearx.org.

Q: What language(s) do you speak?
A: Russian is my native language, but I speak English fluently. I
   generally don't read email in Russian -- English is the language
   of computing. I also speak a little bit of German.

Q: Do you maintain any "public" accounts elsewhere?
A: I am called alearkh on github. The rest that you might be able to
   see either exist for stupid reason, or not needed anymore.

Q: What's up with news/* filenames?
A: The oldest file is called 9999.YYYY-mm-dd, and the latter ones
   reduce the first number by one. This way they can be sorted
   alphabetically, and I am very unlikely to ever run out of
   numbers (and even if I do, I can archive them and restart).

Q: What's up with your domain names?
A: I got my first domain name, and started my first open-source
   projects when I was finishing my university. At the time I allowed
   another student to convince me that a good "internet identity"
   would be a unique, easy to pronounce string (even if meaningless),
   such as those people from reddit or whatever would use. I ended
   up making a website at the domain mcflexy.net. In a short while,
   however, I decided that I should instead allow my (real) name to
   speak for itself, but still didn't want to embed my name into a
   domain name because:

     1) I've got a pretty long name
     2) Most shorter versions I could think of at the time were taken

   So instead I decided to register something that'd read as an
   English word or phrase, and finally came up with mineeyes.cyou.
   I would regret the decision almost immediately, as I discovered a
   lot of spam filters had no trust in .cyous.

   At the time I didn't have a lot of money to begin with, and
   transferring them was becoming a huge problem (it was 2022, and my
   "benevolent" government forbids me from naming the Ukrainian event
   that broke out then). It wasn't too long, however, before I
   graduated from my slave camp, and was hired into another, at which
   point I at least managed to get my bitcoins together and start
   thinking. I registered manpager.net (named after the environment
   variable MANPAGER), and put a notice that mineeyes.cyou is going.
   I also realised at later point that I transferred way too much
   bitcoin (unless I just wanted to renew one domain for the next 20
   years), so I registered a few I thought may be useful later.

   I was happy with the situation for a while, but then I had to
   register on github to participate in a project. Github required me
   to give my user a name (and not just a mail address), but all my
   favourite names for Unix users were already taken, and I didn't
   want to name my user "manpager"! I came up with "drjfaust", as in
   "doctor Johann Faust", but I wasn't happy with it.

   Eventually the idea of catenating first X letters of my first name
   with first Y letters of my surname occurred to me. The method also
   has some flexibility, and can produce funny results. 3 for both X
   and Y seemed to be a good number, so I registered alearx.org (.net
   was a mistake -- it's a TLD for ISPs and the like), and changed my
   github user name to alearkh. The x in alearx is substitute for
   Greek chi.

   That pretty much concludes the situation up until now.

Q: What do you call your Unix users?
A: I usually name my main user aa for my initials. Most of the other
   users, that I might maintain to drop some privileges for certain
   tasks, are usually given short names like "tim" or "jean".

Q: What do you call your hosts?
A: I distinguish between the name(s) by which the host is known on the
   local network, and among friends via /etc/hosts, and the
   publicly-known FQDNs, which are set up via DNS, but also matter
   with web and smtp servers.

   The "local" names are short Unix "words", such as "manpager",
   "cflags", "ex", &c. The FQDNs are just whatever makes sense, while
   being short and memorable.

Q: What about copying your works?
A: When I first began programming, I was perplexed by copyright.
   ("license my program!? it's not a book, or something, you know")
   Then there was a period during which I was extremely confused, and
   now I am just mildly confused.

   Inspecting existing licences I stumbled upon BSD0, which removes
   the attribution clause from the normal BSD licence. So I decided
   to deal with the issue by just putting that into COPYING for each
   of my projects. Many still are distributed this way.

   Later I discovered that the copyright laws don't allow me to
   reject my right to sue people who'd forgotten to attribute my work
   to me, so from that point I decided to instead use OpenBSD's ISC
   licence. I also discovered that further complications arise when a
   project includes files from different sources, so instead I now
   have a licence-comment at the top of each source file.

   Now I believe that some of the text files I publish via gopher may
   be subjects of copyright, so I now also have a small notice at the
   bottom of such files.
