# name of the program (Minix service)
PROG=proj

# source code files to be compiled
SRCS = proj.c video.c utils.c keyboard.c mouse.c timer.c sprite.c dispatcher.c elements.c menus.c game_logic.c

# additional compilation flags
# "-Wall -Wextra -Werror -I . -std=c11 -Wno-unused-parameter" are already set
CFLAGS += -pedantic
CPPFLAGS += -D PROJ

# list of library dependencies (for Lab 2, only LCF library)
DPADD += ${LIBLCF}
LDADD += -llcf

# include LCOM's makefile that does all the "heavy lifting"
.include <minix.lcom.mk>
