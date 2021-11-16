from devices.Device import *


if __name__ == '__main__':
    try:
        device: Device = open_device('/devices/dev3')
        write_line(device)

        for i in range(4):
            print(read_line(device))

    except Exception as exception:
        print(f'Error: {exception}')
