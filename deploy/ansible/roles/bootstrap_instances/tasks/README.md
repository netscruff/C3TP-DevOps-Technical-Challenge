# bootstrap
This task is not required for cloud images that have Python installed.

I was having issues with Xenial cloud images in getting Ansible playbooks
to run on them right after launch. This is not actually required for the
Trusty images that I ended up testing against and I'm still interested in
figuring out what the underlying issue with the Xenial image is and what
the solution would be for cloud images that can't support executing Ansible
modules at launch time.
