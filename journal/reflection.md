#Revisions & the Cloud

#### Local Version Control Systems (VCS)
    *1 database on hard disc that stores changes to files

#### Centralized VCS (CVCS)
    *Ease of collab within team
    *1 database on hard disc that stores changes to files which can be accessed by various CL'stores
    *Eliminates local VCS
    *^ interactivity within team
    *Admin ^ control over revision permissions in team

#### Distributed Version Control (DCVS)
    *CVS is vulnerable and not redundant
    *All work can **kaboom** if CVS goes down or is corrupted
    *DCVS creates mirrored repo's 
    *ease in relacing lost data through previous backups
    *allows simul-workflows

#### What is Git?
    >Snapshots
        *is a DCVS
        *each save/commit creates a new Git Snapshot
    >Local op's 
        *Git's happy place sinc emost info is local
        *expedites process//eliminates history fetch from server
        *can work offline or from VPN
    >Tracking changes   
        *Git sees ALL & will gatekeep corruption or changes
    >Loss of data   
        *Minimizes risk of irreversible loss of data 
    >States
        *Git lives in 3 states:
            1. Committed -- securely stored
            2. Modified -- File changed but not Committed
            3. Staged -- Flagged a file's changed version to be Committed

#### History of Git
    * roots in open src proj Linux kernel
    *first called bitkeeper in 2002
    
#### Computer must be able to read and access git.
    *move through download process!
        >Terminal, your new best friend!

#### Graphical CL's 
    *Graphic User Interface (GUI)

