     ________________-
    < Git is awesome! >
     -----------------
            \   ^__^
             \  (oo)\_______
                (__)\       )\/\
                    ||----w |
                    ||     ||

We had a situation with one of our repos where master was merged up to QA
by accident. So we had to revert the master -> qa merge commit.

The question was, if we merged qa -> master with the revert, and reverted
the revert (see: (this repo)[http://github.com/minusnine/faulty-merge-demo]),
on master, will it persist? Or would would we have to revert the revert on
qa after we merged master back up to qa.

In retrospect, the former makes a lot of sense. This repo verifies it.

If you're confused, it's ok. Your brain is clearly not advanced enough.
