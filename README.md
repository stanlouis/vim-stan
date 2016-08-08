# vim-stan
My vim configuration

base one [marcgg](http://marcgg.com/blog/2016/03/01/vimrc-example/) vim Configuration from scratch.

Leveraging GitHub for backup and portability

To backup keep entire ~/.vim directory within a git repository. 
To restore: git clone https://github.com/stanlouis/vim-stan.git to my .vim directory

For every plugin, you need to run:
```
$ cd ~/.vim
$ git submodule add git@source/pluginname.git bundle/pluginname
```
For instance if you want to add vim-ruby located at https://github.com/vim-ruby/vim-ruby, you’ll do:

```$ git submodule add git@github.com:vim-ruby/vim-ruby.git bundle/vim-ruby```

Later on when you use your config on another machine or want to update your plugins, you’ll be able to use other commands like 
`git submodule init` 
or 
`git submodule update.`
