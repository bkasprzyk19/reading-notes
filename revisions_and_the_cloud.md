This will contain information pertaining to Lab 03 

![git_help](/reading-notes/git_help.png)

<img src="/reading-notes/git_help.png" alt="">



[<==Back](README.md)

<reading-notes[main !+>]$ git add -A
reading-notes[main !+>]$ git commit -m added a page1
error: pathspec 'a' did not match any file(s) known to git
error: pathspec 'page1' did not match any file(s) known to git
reading-notes[main !+>]$ git commit -m 'added some'
[main e958084] added some
 4 files changed, 25 insertions(+), 3 deletions(-)
 create mode 100644 html_structure.md
 rename revisions_and_the_cloud => revisions_and_the_cloud.md (56%)
reading-notes[main *]$ git push origin main
Username for 'https://github.com': bkasprzyk19
Password for 'https://bkasprzyk19@github.com':
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 885 bytes | 885.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/bkasprzyk19/reading-notes.git
   730d2e3..e958084  main -> main>