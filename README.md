# DWM-PowerlineBar
Simple shell script that displays the battery power, uptime, and the current date and time in a powerline theme. Runs on DWM or Nimdow or any other tiling window manager that uses xsetroot.

Make sure that Hack Nerd Fonts, ACPI, and Curl is installed. As this script will not run properly without them.![2022-08-07_10-48](https://user-images.githubusercontent.com/110750401/183296738-6c8e5559-4f34-4e95-a4d0-c783660397c3.png)
![2022-08-14_17-08](https://user-images.githubusercontent.com/110750401/184554959-2beb5636-be53-486c-815a-77e6461411ae.png)

#How To Configure

        ARROW_A=$'\x1b[0m\x1b[38;2;R;G;Bm\x1b[0m\x1b[48;2;R;G;Bm'
        ARROW_B=$'\x1b[38;2;R;G;Bm\x1b[0m\x1b[48;2;R;G;Bm'
        ARROW_C=$'\x1b[38;2;R;G;Bm\x1b[0m\x1b[48;2;R;G;Bm'
        
Copy and paste the statusbar.sh shell script and then you can change the colors of each arrows by using RGB values. Above is to show you where to input the values of the color that you want to change the powerline to.
