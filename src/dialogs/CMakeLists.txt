set(dialogs_SRCS
	${CMAKE_CURRENT_SOURCE_DIR}/actiondialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/actionwitherrortargetsdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/actionwithtargetdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/adjusttimesdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/autodurationsdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/changeframeratedialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/changetextscasedialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/checkerrorsdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/clearerrorsdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/durationlimitsdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/encodingdetectdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/fixoverlappingtimesdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/fixpunctuationdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/insertlinedialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/intinputdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/joinsubtitlesdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/progressdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/removelinesdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/selectablesubtitledialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/shifttimesdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/smarttextsadjustdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/splitsubtitledialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/subtitlecolordialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/syncsubtitlesdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/textinputdialog.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/translatedialog.cpp
	CACHE INTERNAL EXPORTEDVARIABLE
)

set(dialogs_UIS
	${CMAKE_CURRENT_SOURCE_DIR}/encodingdetectdialog.ui
	${CMAKE_CURRENT_SOURCE_DIR}/intinputdialog.ui
	${CMAKE_CURRENT_SOURCE_DIR}/textinputdialog.ui
	CACHE INTERNAL EXPORTEDVARIABLE
)
