# lego-stealth-python

repo for the lego scratch block coding and related materials

1.  please use the http as the img1 shows to copy the repo address

2.  since the Mindstorm Innovator software platform can only be run in windows,
    so please use "git for windows" to do any git operation, here is the downnload address: https://gitforwindows.org/

3.  in the git-bash window, you can use "git clone https://github.com/m-xin/lego-stealth-python.git" ,
    to pull the whole repo to your local machine

4.  please do not directly modify the "master" branch. you need to create your own local branch based on the master to do any modifications

5.  if you believe your scratch code block is able to be used as the final version, you can merge to the master.
    definition of the final version:

    1. you code block schema would not change anymore,
    2. the control parameters are generally comfirmed in your robot platform.

6.  here are some commands as your reference

    <> clone the remote repo to the local machine (only run once, if you never download the repo before)

    $ git clone https://github.com/m-xin/lego-stealth-python.git

    # create your local branch based on master (please use the following style for your branch)

    $ git checkout -b <kid's name>/mission_number_mission_name
    ex: $ git checkout -b williamx/mission1_cinema_mission13_soundtrack

    # Now you can play with your code blacks...

    # when you Temporarily have done your work, please use the following commands to save your work and push to the remote repo

        # added all changes
          $  git add .
        # commit your changes
          $  git commit -m "write a brief msg to indicate your changes, no more than ten words."
        ex: $ git commit -m "finished mission1 para tuning."
        # upload your work to the remote repo (cloud)
          $ git push origin <your branch name>
        ex: $ git push origin williamx/mission1_cinema_mission13_soundtrack

    # additinally, here are some frequenctly-used git commands:

        # check your branch name, and status, such as update, untracked/unsaved modifications etc.
            $ git status
        # check the local branches and its upstreams
            $ git branch -vv
        # check all available branch (local and remote)
            $ git branch -a
        # check the commit record
            $ git log

    # If you have done your work, please merge your changes to the master branch,

    we will use the master branch to deploy the combined code block.

7.  please create a folder with the name of your kid's firstname and last name initial.

8.  in the end, we will combine all kid's work to a filename of 'combined', in the folder mane of "combined".

9.  Here are some useful video links to teach kids to encapsulate their work to a function,
    how to make a PID control, how to use Gyro for straight line movement, and cornering. # gyro turn: https://www.youtube.com/watch?v=nXLXmUY4JnQ # how to use "my block" (i.e. functions/modules in c++ or python): https://www.youtube.com/watch?v=PwSW8L5stmM # PID control: https://www.youtube.com/watch?v=HGwXER0hRMg

10. Please feel free to add items here, Thanks!
