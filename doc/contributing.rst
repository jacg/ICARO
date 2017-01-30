How to contribute to ICARO
=======================

Prepare github
--------------

- `Get a github account
  <https://help.github.com/articles/signing-up-for-a-new-github-account/>`_
  if you do not already have one.

- `Upload your SSH key
  <https://help.github.com/articles/generating-an-ssh-key/>`_, if
  you have not already done so.

Prepare your repositories
-------------------------


- Fork the ICARO repository in GitHub.

- Clone your fork in your local disk.

- set nextic as *upstream*

Use a higher-level git interface
--------------------------------

We believe that the best option is to use `magit <https://magit.vc/>`_ to interact with git: `it's the best git UI <https://magit.vc/quotes/>`_ on the
planet. Magit runs on emacs and we recommend it even if you use another editor. Think of Emacs as the GUI framework in which magit is written.

You will enjoy and learn to understand git much more if you use magit (and besides, *it's free*)

[If you use Mac OS or Windows and want to pay for a commercial product,
https://www.git-tower.com/ seems a reasonable alternative. Otherwise, Just use magit.]

To make the magit experience even better, use
`helm <https://emacs-helm.github.io/helm/>`_.

To make installation of Magit and Helm easier for non-emacs users, we
have prepared an `emacs init file
<https://github.com/nextic/IC/blob/master/doc/init.el>`_ which
installs both and sets some sensible defaults automatically. If you do
not already have an emacs init file, then this file should be placed
in your home directory under `.emacs.d/init.el`. If you *do* have an
existing init file already, then we trust that you know what to do
with the contents of this one.

Read the docs
------------------

See documentation on ICARO and on Notebooks. See also the documentation on IC
