import time

from selenium import webdriver

driver = webdriver.Chrome()


driver = webdriver.Chrome()
driver.get("https://www.facebook.com/")
time.sleep(2)
print(driver.getcurrent_url())
print(driver.gettittle())
print(driver.get_window_position())
print(driver.get_window_size())
driver.maximize_window()
print(driver.get_window_position())
print(driver.get_window_size())
time.sleep(2)


#email=driver.find_element(By.ID,"email").send_keys("surya.laxmi55555.com")

#password=driver.find_element(By.ID,"pass").send_keys("j8147687115")
#time.sleep(1000)
#login=driver.find_element(By.NAME,"login").send_keys(KEY.RETURN)
driver.execute_script("window.scrollTo(0, 0);")
