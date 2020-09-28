### TOC: FAQ

### TOCEntry: ReCodEx

- If you have a [SIS](https://is.cuni.cz/studium) account, you should just
  _Create account_ on https://recodex.mff.cuni.cz/registration.
  - If you are registered for NPFL122 in SIS, you should be automatically added
    to a corresponding group.
  - If you cannot get to a NPFL122 group, _write me, including your
    ReCodEx email_.

- If you have a [SIS](https://is.cuni.cz/studium) account, but the account
  creation fails (this usually happens if you are from a different faculty than
  MFF), _write me, including your SIS login and SIS email_.

- Otherwise, if you have a [CAS](https://ldapuser.cuni.cz/) account, _write me,
  including your CAS email_.

- Otherwise, _write me, including the email you want to be registered with in ReCodEx_.

### TOCEntry: Install

- _Installing to Central User Packages Repository_

  You can install all required packages to central user packages repository using
 `pip3 install --user tensorflow==2.3.1 numpy==1.18.5 gym==0.17.2 box2d==2.3.10`.

- _Installing to a Virtual Environment_

  Python supports virtual environments, which are directories containing
  independent sets of installed packages. You can create the virtual environment
  by running `python3 -m venv VENV_DIR` followed by
  `VENV_DIR/bin/pip3 install tensorflow==2.3.1 numpy==1.18.5 gym==0.17.2 box2d==2.3.10`.
