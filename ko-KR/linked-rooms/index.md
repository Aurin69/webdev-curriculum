---
����: ����� ��
���̵�: HTML & CSS 2
���: ko-KR
embeds: "*.png"
materials: ["Club Leader Resources/*.*","Project Resources/*.*"]
stylesheet: web
...
 
# �Ұ� {.intro}

�� ������Ʈ���� ���� HTML�� �ٹ� ����� ���� ����� ���� ���Դϴ�.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/ba5d27ec68?outputOnly=true&start=result" width="600" height="450" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="rooms-hall-finished.png">
</div>

__����__: ���� Ŭ���Ͽ� �� ���̸� ��������.

# 1 �ܰ�: ���� ������Ʈ������ �ٸ� �������� ��ũ �� �ֱ� {.activity}

�� ������Ʈ�� ���� ���� ��ũ�� HTML ���ϵ�� ������� �� �ֽ��ϴ�. 

## �ܰ躰 üũ����Ʈ { .check}

+ �� Ʈ������ �����ּ���: <a href="http://jumpto.cc/web-rooms" target="_blank">jumpto.cc/web-rooms</a>. Ȥ�� �¶������� �а� �ִٸ�  �Ʒ��� embedded �� Ʈ������ ����� �� �ֽ��ϴ�

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/ef608f0733" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

+ Ʈ������ �ڵ� ����Ǹ� ������ �ִ� �� �� �� �ֽ��ϴ�:

	![screenshot](rooms-hall-start.png)

+ Ʈ������ ���� �� ����Ʈ�� ������. `tvroom.html`�� ã�� Ŭ���ϼ���.

	![screenshot](rooms-tvroom-html.png)

	���� ������Ʈ�� �ٸ� HTML �����Դϴ�


+ `tvroom.html` ���� ������ `index.html`�� ��ũ�� ���ؾ� �մϴ�. 

	������ �ڵ带  `<div>` �ȿ� class `room`�� �Բ� ��������: 

	![screenshot](rooms-link-tvroom.png)

+  __TV Room__ ��ũ�� Ŭ���ؼ� `tvroom.html` �������� ���̴��� Ȯ���غ�����.

	`tvroom.html` ���� �� �������� ���̾ƿ��� �����ϴ� ������ `tvroom.css` ��Ÿ�� ������ �ִٴ� ���� �ָ����ּ���. 

	![screenshot](rooms-tvroom-unstyled.png)

	
##��������: �ٸ� ��ũ ���ϱ� {.challenge}

 `<a>` ��ũ�� `tvroom.html` ���������� ���� `index.html`��� �Ҹ��� ���� �������� ���ư��� ���弼��. ��ũ �ؽ�Ʈ�� 'Hall' �̾�� �մϴ�.

TV Room webpage �� �̷� Ŭ�� ������ ��ũ�� ���ܾ� �մϴ�:

![screenshot](rooms-hall-link.png)

�� �ڵ带 �����غ��� �� ���� ������. �������� TV Room����, �׸��� �ٽ� �������� ��ũ�� Ŭ���ؼ� �� �ٴ� �� �־�� �մϴ�.


## ������Ʈ�� �����ϼ��� {.save}

# 2 �ܰ�: �ٸ� �� ���ϱ� {.activity}

����  __Games Room__�� �߰��� �����ô�. 

+ ������ ���ϱ� __+__ ��ư�� ��������:

	![screenshot](rooms-add-page.png)

	������ �̸��� `gamesroom.html` ���� ��������:

  	![screenshot](rooms-games-html.png)

+ __Games Room__ �� HTML��  `tvroom.html`�� �ſ� ���������  __�����ؼ�__  `gamesroom.html`����  __�ٿ� ��������__.
	
	���� ������ �������� �����ؼ� TV ��� Games��� ������ ���弼��:

	![screenshot](images/rooms-games-html2.png)	

+ ���� `gamesroom.html` �� ���� �������� �ʴ� `gamesroom.css`�� ����մϴ�. 

	������ ���ϱ� __+__��ư�� ������  `gamesroom.css` �� ���弼��. 


+  __Games Room__ �� CSS�� `tvroom.css` �� �ſ� ���������  __�����ؼ�__ `gamesroom.css`��  __�ٿ� ��������__.

	![screenshot](rooms-add-games-css.png)

+ �������� Games Room���� ���� ��ũ�� ���ϼ���:

	![screenshot](rooms-hall-games.png)

+ Games Room ��ũ�� Ŭ���ؼ� ������Ʈ�� �����غ�����.

	__Games Room__ �� �̷��� ���� ���Դϴ�:

	![screenshot](rooms-games-before.png)

	���� ����־� ���̴� �������� �ƴ����� ���� ���������� ��ĥ �� �ֽ��ϴ�.

## ������Ʈ�� �����ϼ��� {.save}

##��������: Games Room ��Ÿ�� �ϰ� ��ũ �ɱ�{.challenge}

__Games Room__�� HTML �� CSS �� �����ؼ� ���������� �̷��� ���̰� ���弼��: 

![screenshot](rooms-games-challenge.png)

��Ʈ:   `gamesroom.css` ���� ����, ��Ʈ ���� �׵θ� ���� �ٲ�� �մϴ�. �� ���� ����� `chartreuse`�� �̸��Դϴ�.  

��Ʈ:  `gamesroom.html`�� `hall.html`�� ��ũ�Ǵ�  `<a>` ��ũ�� ���ؾ� �մϴ�. .

## ������Ʈ�� �����ϼ��� {.save}

# 3 �ܰ�: ��ũ�� ��ó�� ���̰� ����ô� {.activity}

��ũ�� �ؽ�Ʈ�θ� ���� �ʿ�� �����ϴ�.  `<div>`�� ����Ͽ� Ŭ�� �� �� �ִ� ���� ����ô�.

##�ܰ躰 üũ����Ʈ { .check}

+ `index.html`�� ���� __TV Room__ ��ũ �ؽ�Ʈ �ֺ���  `<div>` �� �����ϼ���. `<a>` ���ʿ� �־�� Ŭ�� �˴ϴ�.

  `id="hall2tv"` �� ���ؼ� �������� TV Room���� ���� ������ ���̺� �ؼ� ���� ��Ÿ�� �� �� �ְ� ����ô�. 

  ![screenshot](rooms-tvroom-div.png)  

+  `style.css` ���� Ŭ���ϰ� �� ������ ������ ���� CSS �� ���ؼ� ���� ũ��� ���� �ٲ߽ô�:

	![screenshot](rooms-door-css1.png)

+ ���� Ŭ���ؼ� ���������� Ȯ���غ��ô�.

+ ���� 3�鿡 �׵θ��� ���� �� �� ��ó�� ���̰� ����ô�:

	![screenshot](rooms-door-css2.png)

+ �׸��� CSS�� ���� ���� �ؽ�Ʈ�� �� ���� ���� ������:

	![screenshot](images/rooms-door-css3.png)

+ ���� ���� ���ִ� �� ������ ���Դϴ�. �� �ȿ� ���� �־ ������ ��Ĩ�ô�.

	![screenshot](rooms-door-position.png)	

+ ���� ������  __TV Room__���� �� �� �ִ��� Ȯ���� ���ô�.

## ������Ʈ�� �����ϼ��� {.save}

##��������: �� �� ���ϱ�! {.challenge}

������Ʈ�� �ٸ� ��ũ�鵵 ���� ������� ��ũ�� ������ ���弼��. 

�� ������:

+ �� ��ũ�� `<div>`�� �Ἥ �����ϰ� `hall2games` ���� id�� �Ἥ ��Ÿ�� �Ҽ� �ְ� ���弼��.

	���� ���: 

	`<a href="gamesroom.html"><div id="hall2games">Games Room</div></a>`

+ �� id�� CSS�� ���� `.css` ���Ͽ� ��������. _����_ _�ٿ��ֱ�_�� ����ؼ� �ð��� �Ƴ�����. ���ϽŴٸ� �� ���� �ٸ� ������� ���� �� �ֽ��ϴ�.

+ �� ��ġ�� `bottom:` ��  `left:` �� `right:`�� �Ἥ �����ϼ���.

������ �����Դϴ�:

![screenshot](rooms-hall-doors.png)

TV Room �� �̷��� ������ �մϴ�:

![screenshot](rooms-tvroom-door.png)	


# 4 �ܰ�: ��� �̹��� ���ϱ� {.activity}

������ ��� �̹����� �ٸ纾�ô�.

## �ܰ躰 üũ����Ʈ { .check}


+  `style.css`�� �����ؼ� ������ ��� �̹����� �����սô�:

	![screenshot](rooms-hall-decorated.png)	

	�̹����� �ݺ��Ǿ �� ��ü�� ä�� ���Դϴ�. 


## ������Ʈ�� �����ϼ��� {.save}

##��������: Games Room�� ����� ��������. {.challenge}

games room �� ������� �ٹ� �� �ֳ���?

������Ʈ�� ���Ե�  `space-invader.png` ��� �̹����� �� �� �ֽ��ϴ�.. 

���� �ܰ谡 �ʿ��մϴ�:

+ Games room�� `.room` CSS �� `background-image`�� ���ؾ� �մϴ�.

�ٸ��� ���� �̷� ����Դϴ�:

![screenshot](rooms-games-finished.png)	

## ������Ʈ�� �����ϼ��� {.save}

##��������: ������ ������ ���弼��! {.challenge}

������Ʈ�� �� ���� ���� ���ϼ���. _����_ _�ٿ��ֱ�_�� ����ؼ� �ٲ� �κе鸸 �ٲٸ� �ð��� �Ƴ� �� �ִٴ� �� ���� ������.

�� �濡�� ������ ���� �ܰ谡 �ʿ��մϴ�:

+ `.html` ���� �����
+ �� `room'�� �� ��ũ �����
+ �� ��� ���� ��Ÿ�� ������ `.css` ���� ���ϱ�

�� ���� `background-color.` �� �ٲ� �� �ֽ��ϴ�. �̹��� �������� ������ ��� �̹������� ��󺸼���:

![screenshot](rooms-images.png)	

## ������Ʈ�� �����ϼ��� {.save}

