
if(ANDROID)
    return()
endif()

# Add VST3 Hosting Samples
if(NOT DEFINED SMTG_ADD_VST3_HOSTING_SAMPLES)
    option(SMTG_ADD_VST3_HOSTING_SAMPLES "Add VST3 Hosting Samples to the solution" ON)
endif()

include(SMTG_AddSubDirectories)

smtg_add_subdirectories()
