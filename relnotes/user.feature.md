* Internal `cachalot` user

  As part of base image generation, user named `cachalot` is now created. It is
  intended to be used to run tests without accidental root access which may
  affect the result.

  This user is added to sudoers with a permission to run any sudo command
  without a password.
