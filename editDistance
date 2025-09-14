# geek for geeks and AI
import nltk
from nltk.corpus import words
import threading
import time

nltk.download('words')
english_words = words.words()

print(len(english_words))  
print(english_words[:10])  


def editDistRec(s1, s2, m, n):
    if m == 0:
        return n

    if n == 0:
        return m

    if s1[m - 1] == s2[n - 1]:
        return editDistRec(s1, s2, m - 1, n - 1)

    return 1 + min(editDistRec(s1, s2, m, n - 1),
                   editDistRec(s1, s2, m - 1, n),
                   editDistRec(s1, s2, m - 1, n - 1))


def editDistance(s1, s2):
    return editDistRec(s1, s2, len(s1), len(s2))


l = [[i for i in english_words if i[0]==c or i[0]==c.upper()] for c in "abcdefghijklmnopqrstuvwxyz"]


def worker(s1,l):
    for w in l:
        if editDistance(s1,w)<=1:
            print("{}:  {}".format(s1,w))
            
s1 = input("Enter a word: ")

t1 = threading.Thread(target=worker, args=(s1,l[0]))
t2 = threading.Thread(target=worker, args=(s1,l[1]))
t3 = threading.Thread(target=worker, args=(s1,l[2]))
t4 = threading.Thread(target=worker, args=(s1,l[3]))
t5 = threading.Thread(target=worker, args=(s1,l[4]))
t6 = threading.Thread(target=worker, args=(s1,l[5]))
t7 = threading.Thread(target=worker, args=(s1,l[6]))
t8 = threading.Thread(target=worker, args=(s1,l[7]))
t9 = threading.Thread(target=worker, args=(s1,l[8]))
t10 = threading.Thread(target=worker, args=(s1,l[9]))
t11 = threading.Thread(target=worker, args=(s1,l[10]))
t12 = threading.Thread(target=worker, args=(s1,l[11]))
t13 = threading.Thread(target=worker, args=(s1,l[12]))
t14 = threading.Thread(target=worker, args=(s1,l[13]))
t15 = threading.Thread(target=worker, args=(s1,l[14]))
t16 = threading.Thread(target=worker, args=(s1,l[15]))
t17 = threading.Thread(target=worker, args=(s1,l[16]))
t18 = threading.Thread(target=worker, args=(s1,l[17]))
t19 = threading.Thread(target=worker, args=(s1,l[18]))
t20 = threading.Thread(target=worker, args=(s1,l[19]))
t21 = threading.Thread(target=worker, args=(s1,l[20]))
t22 = threading.Thread(target=worker, args=(s1,l[21]))
t23 = threading.Thread(target=worker, args=(s1,l[22]))
t24 = threading.Thread(target=worker, args=(s1,l[23]))
t25 = threading.Thread(target=worker, args=(s1,l[24]))
t26 = threading.Thread(target=worker, args=(s1,l[25]))

t1.start()
t2.start()
t3.start()
t4.start()
t5.start()
t6.start()
t7.start()
t8.start()
t9.start()
t10.start()
t11.start()
t12.start()
t13.start()
t14.start()
t15.start()
t16.start()
t17.start()
t18.start()
t19.start()
t20.start()
t21.start()
t22.start()
t23.start()
t24.start()
t25.start()
t26.start()


t1.join()
t2.join()
t3.join()
t4.join()
t5.join()
t6.join()
t7.join()
t8.join()
t9.join()
t10.join()
t11.join()
t12.join()
t13.join()
t14.join()
t15.join()
t16.join()
t17.join()
t18.join()
t19.join()
t20.join()
t21.join()
t22.join()
t23.join()
t24.join()
t25.join()
t26.join()
