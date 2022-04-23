This is an `Ansible` playbook to use for the automating of `Windows` hosts patch updates. 

This should work for hosts running any version of `Windows` OS.

It is meant to be run from `Ansible Tower` or `AWX-Operator` environments, however it can be easily adapted to run with an inventory and `Ansible-Core` CLI environments as well.

---

This will create a log file when run for auditing purposes. It will save the following file on the `C:\` drive

```
C:\ansible_wu.txt
```