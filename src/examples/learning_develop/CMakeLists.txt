px4_add_module(
	MODULE examples__learning_develop
	MAIN learning_develop
	STACK_MAIN 2000
	SRCS
		learning_develop.c
	DEPENDS
	)
