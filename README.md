# Install

Use pathogen and clone this into your `$VIM/bundle` directory.

If not using pathogen, copy the contents of `doc` into `$VIM/doc` and do a `:helptags $VIM/doc` to generate the tag list.

# Using

When editing a Java file:

    :help ArrayList

I find it helpful to do:

    set keywordprg=

in my `.vimrc` so that the "K" command will look up the javadoc of the class I'm on

While hovering over a class name you can type <C-r> <C-w> while in the command-line mode 
and it will paste the name.
# Make your own

http://davetron5000.github.com/vimdoclet/
