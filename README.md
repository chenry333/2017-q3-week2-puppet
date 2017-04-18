2017 Q3 Unix/Linux 110 A/B Ansible demo

Copy these files into your /etc/pupppet directory and:

- Install puppet librarian: ```apt-get install librarian-puppet```

- Install modules defined in Puppetfile: ```sudo librarian-puppet install```

- Run site_testing.pp (applies testing module): ```sudo puppet apply site_testing.pp```

More examples at https://github.com/voxpupuli/librarian-puppet#example-puppetfile

