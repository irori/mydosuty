PATACD: Generic ATAPI CD-ROM driver for DOS (IBM PC and NEC PC-98)

NEC PC-9821 �V���[�Y�������� PC/AT �݊��@�p�� IDE (ATAPI) CD-ROM
�h���C�o�ł��B�o�[�W���� 3.1 �ȏ�� MS-DOS�AWindows 95/98/Me ��
�V���O�� MS-DOS ���[�h�ŗ��p�\�ł��B
�iCD-ROM ���̃t�@�C���A�N�Z�X�ɂ́AMSCDEX �������͌݊��h���C�o��
�ʓr�K�v�ł��j

�Ȃ� PATACD.SYS �P�̂� PC-98 �� PC/AT ���p�ƂȂ��Ă��܂��B


�C���X�g�[��
------------

���� DOS �p CD-ROM �h���C�o�Ɠ��l�ɁADOS �� config.sys �� device ����
�h���C�o�̃t���p�X�����L�q���A�f�o�C�X�h���C�o�Ƃ��ēo�^���܂��B

DEVICE=[<�h���C�u>:][<�p�X>]PATACD.SYS [/D:�f�o�C�X��]

�f�o�C�X���� MSCDEX �ɓn���h���C�o�̃f�o�C�X�����p�����W�����ȓ���
�ݒ肵�܂��B
/D �I�v�V�������w�肵�Ȃ��ꍇ�A

  NEC PC-98 �V���[�Y�ł� /D:CD_101
  IBM PC/AT �݊��@�ł� /D:MSCD001

���w�肵�����̂Ƃ݂Ȃ���܂��B


������
--------

�E�p������ ATA �ڑ���p�BSATA �ڑ��͖��Ή��ł��B
�E����قǓ���͈��肵�Ă��܂���B
  �G�~�����[�^�E���z�}�V����ł͂���Ȃ�ɓ��삷��Ǝv���܂��i�v�������j�B
�ECD-ROM �h���C�o�̋@�\���t���T�|�[�g���Ă���킯�ł͂���܂���
�E�I�[�f�B�I�`�����l���i���ʁj����̓f�t�H���g�Ŗ����ƂȂ��Ă��܂��B
  �K�v�ȏꍇ�̓\�[�X���� %define SUPPORT_AUDIO_CHANNEL �̐擪�ɂ���
  �R�����g�i;�j�������čăr���h���Ă��������B
  �i240�o�C�g�قǃT�C�Y�������܂��j
�ECD �Đ��� CD-ROM �h���C�u�̃A�i���O�����o�͂��特���o�͂���܂��B��������
  �h���C�u���A�i���O�Đ��R�}���h���T�|�[�g���Ă��Ȃ�������A�A�i���O�o�͂�
  �ǂ��ɂ��ڑ�����Ă��Ȃ��ꍇ�ACD �Đ����͏o�܂���B


�\�[�X
------

  https://github.com/lpproj/mydosuty/tree/master/patacd


