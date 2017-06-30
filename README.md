# GCC_offload_compiler_specifics
Commands, flags, dependencies required for building GCC offload compiler from source. (for GPU implementions)

GCC offlaod compiler is needed to use the openACC compiler directives, thus offloading computations to GPU.
nvptx tools nvptx-newlib will be needed to build offload compiler from source.

Dependencies:  nvptx-tools and nvptx-newlib (downloadable from github).

nvptx-tools: https://github.com/MentorEmbedded/nvptx-tools
nvptx-newlib: https://github.com/MentorEmbedded/nvptx-newlib
