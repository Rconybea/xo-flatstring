# xo-flatstring/docs/CMakeLists.txt

xo_doxygen_collect_deps()
xo_docdir_doxygen_config()
xo_docdir_sphinx_config(index.rst install.rst lessons.rst flatstring-reference.rst flatstring-class.rst)
