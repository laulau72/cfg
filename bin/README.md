
# bin directory

# Table of Contents

   * [config.hostname](#config.hostname)
   * [config.hosts](#config.hosts)
   * [config.sshd_config](#config.sshd_config)

---


### config.hostname

 Set hostname to the short hostname, without FQDN.
 Should be run on AIX server only

---
### config.hosts

 Setup /etc/hosts

---
### config.sshd_config

 Configure sshd's sshd_config

#### Input:

 -d ssh_dir	Location of the ssh directory (default: /etc/ssh)

#### Ouput:

 sshd_config 	Generated with etc/sshd_config-generator and cfg/etc/sshd-settings

#### Return code:

 *  0:        Ok
 *  1:	Can not find ssh settings file
 * 22:	Usage

---
