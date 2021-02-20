# ansibe-password-update
update users password using ansible
# How to use
open update_password.yml and change the name of the user you want to update password. then use bellow command to update user password:
    ansible-playbook -i hostfile change-password.yml --extra-vars newpassword=12345678
remmber to change newspassword value to password that you want to change.
