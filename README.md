# Rsync Intro --- An Instruqt Example Track

This is an example three challenge Instruqt track, designed
to show off the basics of how a track works.

## Requirements

You must create a [Custom Resource](https://docs.instruqt.com/sandboxes/manage/custom-resources)
in your account, and add the [terraform-instruqt-sshkey](https://registry.terraform.io/modules/instruqtkula/sshkey/instruqt/)
module as a custom resource named `sshkey`.

**ALSO NOTE**: Due to a current (April 2026) limitation in the Intruqt
CLI tool, the custom resource configuration is not included here. In
order to use this track, after you have added the `sshkey` custom resource
to your Intruqt team per above, you must also [add a custom resource](https://docs.instruqt.com/sandboxes/manage/custom-resources#use-custom-resources)
to this track called `iggys-key` which is an instance of the `sshkey`
custom resource. You must do this any time you push the track to Instruqt.
