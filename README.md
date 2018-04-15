import os
import pygame
from pygame.locals import*
from random import *


pygame.init()
taille_fenetre = (600, 600)
fenetre_rect = pygame.Rect((0,0), taille_fenetre)
screen_surface = pygame.display.set_mode(taille_fenetre, pygame.FULLSCREEN)




pygame.quit()
