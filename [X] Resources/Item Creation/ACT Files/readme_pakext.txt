�J�ɓ]�����Ă�data.grf��extract�A���̑����ł��܂��B
��{�I��Win2k/XP�p�ł����A�����̃c�[���ƈ����98/Me���[�U�[�ɈՂ����ł��B
�i�R�s�[���C�g�͂��̃t�@�C���̉��̕��j

DOS�v�����v�g�A�R�}���h�v�����v�g����
pakext -h�@�ŁA����`���Ǝg�������\������܂��B
�t�B�[�����O�Ŏg���Ă�������

�g������i�����܂ł���ł��j

�O�D�C�[�W�[���[�h
�@pakext -E data.grf
�@�܂��A�c���[�̒��őΏۂ�I�����Ă���{�^���������Ă��������B
�@�N�����x���ꍇ�́A
  �@pakext -m .spr data.grf
�@�Ƃ��āA�i�荞�݂܂��傤

�P�D���X�g�̍쐬
�@pakext -t data.grf

�Q�D�S�W�J�i��98/Me�̓_���j
�@pakext data.grf

�R�D�����W�J�i��98/Me�̓_���j
�@�@�@pakext -m sprite data.grf
�Ƃ��@pakext -m .txt data.grf

�S�D�J�����g��data�t�H���_�ȉ��̃p�b�`�쐬�i�v -k�t���ł̓W�J�j�i��98/Me�̓_���j
�@pakext -p (or -P) -k

�T�D�p�b�`���āi���R���p�C���ς�exe����͍폜����Ă܂��j
�i����Ȃ�Ɉ��肵�Ă�Ǝv���܂��j
�@pakext -a update.gpf data.grf

�U�D�L�����N�^�r���[���[
  pakext -C data.grf
 ��Apakext -C data.grf update.gpf
  �}�E�X���h���b�O�ŃY�[��
  �E�h���b�O�ňړ�

�V�D�����폜�i���`���͂��܂������Ă܂���B�v�o�b�N�A�b�v�j
�i���R���p�C���ς�exe����͍폜����Ă܂��j
�@pakext -s sdata.grf data.grf
 �Ƃ���ƁAsdata.grf���̂���f�[�^��data.grf���̓���̂��̂Ȃ�΍폜���܂��B
�@�isdata.grf - data.grf �� ��v�����f�[�^�𔲂���sdata.grf�j
  pakext2 -S data.grf update.gpf
 �Ƃ���ƁAdata.grf���̂���f�[�^��update.gpf���ɂ���t�@�C����������̂��̂Ȃ�폜���܂��B
�@�idata.grf - update.gpf �� ��v�����t�@�C�����̃f�[�^�𔲂���data.grf�j
�@-s�̎g�����͌��Ă��̂܂܂ł����A-S�̎g�����͂�����ƍl���Č��܂��傤�B
�@�֗��ł���ˁH�ˁH


Win98/ME�Ńp�b�`��肽���Ƃ��iWin 2k/XP�ł��j
�i���R���p�C���ς�exe����͍폜����Ă܂��j
���F�r���o�Ă���list.txt��ҏW���ăZ�[�u���Ȃ��ł�������
�@�@���R�́A�u�E�v�̕����R�[�h���ϊ�����鋰�ꂪ���邩��ł�

Step1 ���X�g�t�@�C���̍쐬
 DOS�v�����v�g��
�@pakext2 -t -k data.grf > list.txt
 �Ƃ��āA���X�g�t�@�C��list.txt���쐬���܂��B

Step2 �Ή��t�@�C���̍쐬
 �ʂ̃e�L�X�g�t�@�C�����ȉ��̌`���ō쐬���܂��B

(����)(�^�u)(�����ŗp�ӂ����t�@�C����)

��. (����example_vs.txt���Q�l�ɂ��Ă��������j
5088	c:\tmp\a.spr
3	a.act

 �����ɂ��鐔���́A��ɍ�������X�g�t�@�C���ɏ�����Ă��鐔���ł��B
���̐������L�[�Ƃ��āA�Ή��t�@�C���ɏ����ꂽ�t�@�C�����ɑΉ�������킯�ł��B
�؍��ꂪ�ǂ߂�l�́AStep1��hangle.html�Ƃ����t�@�C����������
�쐬���Ă���̂Łi-t���� -k���g���Ƃ����Ȃ�j�A���������Q�l�ɂ��Đ�����
�T���Ă��������B
 �n���O�����ǂ߂Ȃ��ꍇ�́Asjis-euckr-unicode.html (�ǋL�S)���Q�l�ɂ��Ă�������

 �����ō쐬�����Ή��t�@�C���̃t�@�C����������vs.txt�Ƃ��܂��B

Step3 �N��
 DOS�v�����v�g����
 pakext -9
�ł�

Step4 �t�@�C���̃Z�b�g
 ���X�g�t�@�C��(list.txt)�A�Ή��t�@�C��(vs.txt)�̂��ꂼ����Q�ƃ{�^����
�����ăZ�b�g���Ă�������

Step5 �m�F
 �Ή��̊m�F�{�^���������āA�t�@�C�����̑Ή������Ă��邩�m�F���Ă�������
(�����ŗp�ӂ����t�@�C����)
 -> (data.grf���̃t�@�C�����j
�ƕ\�������͂��ł�

Step6 �쐬
 �p�b�`�̃o�[�W������I�����āAupdate.gpf�쐬�{�^���������č쐬���Ă�������
�����A�J�����g�f�B���N�g����update.gpf���쐬����܂�

�菇���ʓ|�ł����A���ׂĂ�SJIS�̃R�[�h������āA�W���ɂ�����Ђ̂����ł��B
�E�B���h�E���������ꍇ��
pakext -9 [-p or -P] -l ���X�g�t�@�C���� -T �Ή��t�@�C���� 
�ŁA�R�}���h�v�����v�g��ŏI�����܂��B
�i-p ��ver.2�`�� -P��ver.1�`���B�����t���Ȃ���ver.1�`���j
�i���R���p�C���ς�exe����͍폜����Ă܂��j




COPYRIGHT

    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 2 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program; if not, write to the Free Software
    Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA

�ǋL�F
�@grf�̓W�J������Athena�̃R�[�h���ꕔ�g�p���Ă��܂�

�ǋL�Q�F
�@�|

�ǋL�R�F
�@���R���p�C���́Awin��VC++�ŁAlinux��gcc/g++�ŁB
�@linux�ł�gtk+2.2���g���Ă܂��B�ق���gtkglext���K�v�B
  windows�ł̍ăR���p�C���́A
�@  ��pakext-gtk�Aactor-gtk�v���W�F�N�g���폜����
  �܂��́A
�@  ��http://gladewin32.sourceforge.net/��all in one installer���C���X�g�[����
�@�@  VC (or VS)�̐ݒ�
  ������K�v������܂�

�ǋL�S�F
�@���� share\locale\ja\LC_MESSAGES\grfviewer.l.mo��K���ɕ��ׂ����̂ŁA���g�p�̂��̂��������Ă܂�

�ǋL�T�F
�@�@�a�󂪋C�ɓ���Ȃ��ꍇ�́Ashare\locale\ja\LC_MESSAGES\grfviewer.l.mo
�@�̃t�@�C�����@msgunfmt���āA��������̏��������Ă��������B
�@�i��������A.po��t������Ęb������܂����c�B�A�C�e�����̏o�����c�j


windows�ł̍ăR���p�C���́A
�@��pakext-gtk�Aactor-gtk�Arsmview-gtk�v���W�F�N�g���폜����
�܂��́A
�@��http://gladewin32.sourceforge.net/��all in one installer���C���X�g�[����
�@�@VC (or VS)�̐ݒ�
    libintl.h�� �W����fprintf���g�p����悤�ɕύX
    zconf.h�� HAVE_UNISTD_H�̒�`���Ԉ���Ă���̂��C��
    
������K�v������܂�
