# eapol_test_count_retries

eapol_test that counts the number of retries of RADIUS Access-Request

# Apply patche

`
$ wget http://w1.fi/releases/wpa_supplicant-2.4.tar.gz 
$ tar xvf wpa_supplicant-2.4.tar.gz 
`

cp patch file to wpa_supplicant-2.4

`
$ cd wpa_supplicant-2.4 
$ patch -p0 -d . < wpa_supplicant-count_retries.patch 
`


