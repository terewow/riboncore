
########### install files ###############

FILE(GLOB _SQL_TOOLS *.sql)

install(FILES ${_SQL_TOOLS} README DESTINATION share/ribon/sql/tools)
