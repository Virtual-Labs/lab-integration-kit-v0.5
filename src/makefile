DEST=build

all:  publish

publish: init
	emacs --script elisp/publish.el

init:
	mkdir -p ${DEST}
	cp -r ./ovpl-kit/ovpl-docs/ ${DEST}
	cp -r ./ovpl-kit/ovpl-scripts ${DEST}
	cp -r ./ui-tool-kit/ui-docs/ ${DEST}
	cp -r ./ui-tool-kit/ui-scripts ${DEST}
	cp -r ./ui-tool-kit/ui-src ${DEST}

clean:
	rm -rf ${DEST}
