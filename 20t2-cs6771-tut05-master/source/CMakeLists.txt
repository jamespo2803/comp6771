cxx_executable(
   TARGET subscript
   FILENAME "subscript.cpp"
   LINK range-v3 gsl::gsl-lite-v1
)

cxx_executable(
   TARGET rethrow
   FILENAME "rethrow.cpp"
   LINK range-v3 gsl::gsl-lite-v1
)

cxx_executable(
   TARGET catchbad
   FILENAME "catchbad.cpp"
   LINK range-v3 gsl::gsl-lite-v1
)
