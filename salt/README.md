## Master
- Run debug mode: salt-master -l debug
- States dir: /srv/salt
- States tutorial: http://docs.saltstack.com/en/latest/topics/tutorials/states_pt1.html#sls-file-namespace
- List keys: salt-key -L
- Accept keys: salt-key -A
- Test commands: salt '*' test.ping | salt '*' disk.usage | salt '*' cmd.run 'ls -l /etc' | salt '*' pkg.install vim

## Minions
- Config master ip: /etc/salt/minion
- Run debug mode: salt-minion -l debug 
