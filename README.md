# ts22208-repro
Reproduction for https://github.com/microsoft/TypeScript/issues/22208

lib.ts was already compiled using tsc -d lib.ts and the resul;ting lib.d.ts file moved to the dist/ folder

from the root folder run:

tsc -p src
<BR> or <BR>
tsc -p src --noResolve

fails with an error. 
