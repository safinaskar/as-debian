cmake_minimum_required (VERSION 3.0.2) # 3.0.2 подходит
project (as-debian LANGUAGES)
install (FILES as-debian DESTINATION bin)
install (PROGRAMS gen-sources download-deb DESTINATION bin)
install (FILES mirrors DESTINATION share/as-debian)
