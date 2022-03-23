import pandas as pd
import numpy as np
import random

def randata(howlong=100, randomstart=-10, randomstop=10, startnum=0):
    num = startnum
    i = 0
    longlist1 = []
    longlist2 = []

    df = pd.DataFrame({
        'nums1': [],
        'nums2': []
    })
    while i < howlong:
        longlist1.append(num)
        if i == howlong:
            break

        num = num + random.randint(randomstart, randomstop)
        i = i + 1
    num = startnum
    i = 0

    while i < howlong:
        longlist2.append(num)
        if i == howlong:
            break


        num = num + random.randrange(randomstart, randomstop)
        i = i + 1


    df.nums1 = longlist1
    df.nums2 = longlist2

    return df


dataframe = randata(500, -10, 10, 80)
print(dataframe)
