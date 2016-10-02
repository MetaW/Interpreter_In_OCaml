# Interpreter_In_OCaml

An exercise for getting started with OCaml, ocamllex, ocamlyacc and merlin.

-----
# Compile and run

```
$ git clone https://github.com/MetaW/Interpreter_In_OCaml.git

$ cd Interpreter_In_OCaml/

$ ocamlbuild -use-menhir -tag thread -use-ocamlfind -quiet -pkg core src/run.native

$ ./run.native
```
