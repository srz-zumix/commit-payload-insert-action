build: dist/main/index.js

dist/main/index.js: src/main/index.js Makefile package-lock.json
	npx ncc build $< -o dist/main

package-lock.json: package.json
	npm install
