DEST=build

all:  publish

publish: init
	emacs --script elisp/publish.el

init:
	mkdir -p ${DEST}
	cp -r ./ovpl-kit/docs/ ${DEST}
	cp -r ./ovpl-kit/scripts ${DEST}

clean:
	rm -rf ${DEST}
