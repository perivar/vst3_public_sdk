
if(ANDROID)
    add_subdirectory(adelay)
    return()
endif()

# PIN: disable samples by commenting out the following two lines
include(AddSubDirectories)
add_subdirectories()

# PIN: instead compile one and one sample
# add_subdirectory("again")
# add_subdirectory("hostchecker")
# add_subdirectory("note_expression_synth")
