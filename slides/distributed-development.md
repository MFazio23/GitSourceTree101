##Distributed Development

<img src="img/cvcs-vs-dvcs.svg" />

Note:
+ SVN/CSV are centralized VCS
    + One central repo, each user has a local working copy
+ Git is a distributed VCS
    + Each user has a local repository
        + Full history of commits
+ Full history means fewer network calls for commits/history
+ Easier to scale
    + Breaking _develop_ branch in SVN means nobody can check anything in
    + Breaking _develop_ branch in Git still means people can work locally 