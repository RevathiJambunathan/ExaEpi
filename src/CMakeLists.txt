# List of source files
set(_sources
         main.cpp
         AgentDefinitions.H
         AgentContainer.H
         AgentContainer.cpp
         CaseData.H
         CaseData.cpp
         DiseaseParm.H
         DiseaseParm.cpp
         DemographicData.H
         DemographicData.cpp
         Initialization.H
         Initialization.cpp
         IO.H
         IO.cpp
         InteractionModel.H
         InteractionModGeneric.H
         InteractionModHome.H
         InteractionModNborhood.H
         InteractionModSchool.H
         InteractionModWork.H
         InteractionModelLibrary.H
         Utils.H
         Utils.cpp)

# List of input files
set(_input_files )

setup_agent(_sources _input_files)

unset( _sources )
unset( _input_files )
