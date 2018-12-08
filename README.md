# Read Me

## Contents

##### [About](#about-) \| [Who](#who-) \| [What](#what-) \| [Where](#where-) \| [Why](#why-) \| [How](#how-)

#### [Notes](#notes-)

##### [Note 1](#note-1-) \| [Note 2](#note-2-)

#### [Appendix](#appendix-)

##### [.gitattributes](#gitattributes-) \| [.gitignore](#gitignore-) \| [.exclude](#exclude-)

### [Credits](#credits-)

* * *

## About [≪](#read-me)

This is a starter repo.

### Who [≪](#read-me)

Your Mom's blank repo.

### What [≪](#read-me)

AKA Chasing the em repo.

-   [x] A
-   [ ] B
    -   [ ] C
    -   [ ] D
-   [ ] E

### Where [≪](#read-me)

Built local with an Atom editor on a Win 10 64 host and `git` on a VboxVM for an Ubuntu guest .

### Why [≪](#read-me)

Blank

### How [≪](#read-me)

`Bitnami nodejs stack>npm`
Windows hosts with Linux guests that share folders have issues with symlinks created from within the guest because Win 10 64 doesn't support such links in a way that doesn't take all year to execute. `NPM` does not install local packages on a Linux guest on a Win host, when the pkg has symlinks, at all as of now. However, Bootstrap and its dependencies do not have such issues but the `node` and `npm` v* may be a problem.
```npm i -D shelljs shx mocha should dart-sass fibers eslint stylelint stylelint-scss requirejs materialize-css```
[ESLint rules](https://eslint.org/docs/rules/)
[Configuring ESLint](https://eslint.org/docs/user-guide/configuring)
[Configuring stylelint](https://stylelint.io/user-guide/configuration/)
* * *

## Notes [≪](#read-me)

### Note 1 [≪](#read-me)

### Note 2 [≪](#read-me)

* * *

## Appendix [≪](#read-me)

### .gitattributes [≪](#read-me)

> Git attribute data also allows you to do some interesting things when exporting an archive of your project.

```markdown
.git                    export-ignore
.gitignore              export-ignore
.gitattributes          export-ignore
.travis.yml             export-ignore
codesniffer.ruleset.xml export-ignore
```

<https://git-scm.com/book/en/v2/Customizing-Git-Git-Attributes#Exporting-Your-Repository>

### .gitignore [≪](#read-me)

```*~
_site
.sass-cache
node_modules
# blank*
# assets/vendor

####################################################
# https://help.github.com/articles/ignoring-files/ #
####################################################

###################
# Compiled source #
###################
*.com
*.class
*.dll
*.exe
*.o
*.so

############
# Packages #
############
# it's better to unpack these files and commit the raw source
# git has its own built in compression methods
*.7z
*.dmg
*.gz
*.iso
*.jar
*.rar
*.tar
*.zip

######################
# Logs and databases #
######################
*.log
*.sql
*.sqlite

######################
# OS generated files #
######################
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
ehthumbs.db
Thumbs.db
*.nfo

##################
# Ruby.gitignore #
##################

Gemfile
/tmp/

## Environment normalization:
/.bundle/
/vendor/bundle
/lib/bundler/man/

# for a library or gem, you might want to ignore these files since the code is
# intended to run in multiple environments; otherwise, check them in:
Gemfile.lock
# .ruby-version
# .ruby-gemset

# unless supporting rvm < 1.11.0 or doing something fancy, ignore this:
.rvmrc

####################
# Jekyll.gitignore #
####################

_site/
.sass-cache/
.jekyll-cache/
.jekyll-metadata

################################################
# npm_modules.gitignore dependency directories #
################################################

# node_modules/
```

### .exclude [≪](#read-me)

* * *

### Credits [≪](#read-me)

Third party resources applied in this repo. Each resource uses a GPL compatible license. The resources are listed according to each individual license, as noted, and have links where applicable.

\*
  \*
