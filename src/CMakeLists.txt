set(OpenGlLinkers -lglut -lGLU -lGL -lglfw -lGLEW)
add_executable(ThreeBodyProblem
        main.cpp
        )
target_link_libraries(ThreeBodyProblem ${OpenGlLinkers})