Cách cài đặt các công cụ cần thiết :
	Cài đặt python phiên bản 2.7
	Download file ez_setup.py tại đường dẫn https://bitbucket.org/pypa/setuptools/raw/bootstrap/ez_setup.py và chạy
	Sau khi chạy xong, ta sẽ có file easy_install tại thư mục scripts của Python.
	Ta tiến hành chạy các câu lệnh sau với file easy_install :
	easy_install robotframework-selenium2library
	easy_install robotframework
	easy_install selenium
	easy_install decorator
	easy_install docutils
	Như vậy ta đã hoàn thành quá trình cài đặt.
Để chạy các test case cho các module, tiến hành:
	Mở giao diện command line.
	Dịch chuyển đến thư mục chứa các file ClassTest.txt.
	Chạy lệnh "pybot ClassTest.txt" (không bao gồm dấu "...")
	Xem kết quả.
