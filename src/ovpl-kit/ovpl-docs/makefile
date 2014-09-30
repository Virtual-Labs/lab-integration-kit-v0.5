DEST=build/

all:  publish

publish: init
	emacs --script elisp/publish.el

init:
	mkdir -p ${DEST}
