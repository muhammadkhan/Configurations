BASEDIR=~

.PHONY: update unpack

update:
	cp $(BASEDIR)/.emacs dotemacs
	cp -r $(BASEDIR)/.emacs.d/* ./EmacsDotD/

unpack:
	cp dotemacs $(BASEDIR)/.emacs
	cp -r ./EmacsDotD/* $(BASEDIR)/.emacs.d/
