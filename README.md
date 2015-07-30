# Joou-s-Config

## Vim Plugins

* syntastic: https://github.com/scrooloose/syntastic
* Nerdtree: https://github.com/scrooloose/nerdtree
* xptemplate: https://github.com/drmingdrmer/xptemplate
* [Ctags/Taglist/Cscope/Winmanager/NERDTree/OmniCppComplete](http://blog.csdn.net/bokee/article/details/6633193)

## Clear backup files(~)

	find . -name "*~" > ToBeClear.sh
	chmod +x ToBeClear.sh
	(Add rm, sort multi-lines to one line by "shift j")
	./ToBeClear.sh
