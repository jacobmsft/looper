# looper
Easy mechanism to create a daemon which loops over a function

'''

    from oss.utils.looper import Looper

    looper = Looper()
    looper.capture_signals()

    sleep_interval = 15 # seconds
    looper.loop(sleep_interval, run_once) 

    def run_once():
        # do stuff
    
'''
