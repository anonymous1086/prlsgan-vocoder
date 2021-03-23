# <center> Improve GAN-based Neural Vocoder using Pointwise Relativistic Least Square GAN </center>

<center> Anonymous submission </center>

## Abstract
Recently, GAN-based neural vocoders, such as Parallel WaveGAN and MelGAN have attracted great interest due to their lightweight and parallel structures, enabling them to generate high fidelity waveform in a realtime manner. In this paper, inspired by Relativistic GAN, we introduce a novel variant of the LSGAN framework under the context of waveform synthesis, named Pointwise Relativistic LSGAN (PRLSGAN). In the proposed framework, we take the truism score distribution into consideration and combine the original MSE loss with the proposed pointwise relative discrepancy loss to increase the difficulty of the generator to fool the discriminator, leading to improved generation quality. Moreover, PRLSGAN is a general-purposed framework that can be combined with any GAN-based neural vocoder to enhance its existing generation quality. Experiments have shown a consistent performance gain based on Parallel WaveGAN and MelGAN, demonstrating the effectiveness and strong generalization ability of PRLSGAN based neural vocoders. 

## Audio Samples (Chinese; biaobei dataset)


Text: 花园口与将军坝：到郑州看黄河，必然先到花园<div class="text-red bg-red-light mb-2">口</div>。

| ** A ** | ** B ** | ** C ** | ** D ** | **E ** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="wavs/009815/gt.wav" controls preload></audio> | <audio src="wavs/009815/melgan.wav" controls preload></audio> | <audio src="wavs/009815/melgan_prls.wav" controls preload></audio> | <audio src="wavs/009815/pwgan.wav" controls preload></audio> | <audio src="wavs/009815/pwgan_prls.wav" controls preload></audio> |

Text: 不过，网友都纷纷支持应采儿这一霸气行为。

| ** A ** | ** B ** | ** C ** | ** D ** | **E ** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="wavs/009564/gt.wav" controls preload></audio> | <audio src="wavs/009564/melgan.wav" controls preload></audio> | <audio src="wavs/009564/melgan_prls.wav" controls preload></audio> | <audio src="wavs/009564/pwgan.wav" controls preload></audio> | <audio src="wavs/009564/pwgan_prls.wav" controls preload></audio> |

Text: 在事发的幺四零二室门口还有大摊的血迹。

| ** A ** | ** B ** | ** C ** | ** D ** | **E ** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="wavs/009318/gt.wav" controls preload></audio> | <audio src="wavs/009318/melgan.wav" controls preload></audio> | <audio src="wavs/009318/melgan_prls.wav" controls preload></audio> | <audio src="wavs/009318/pwgan.wav" controls preload></audio> | <audio src="wavs/009318/pwgan_prls.wav" controls preload></audio> |

Text: 绑匪给她穿上了自杀式炸弹背心，在营救人员到来时引爆。

| ** A ** | ** B ** | ** C ** | ** D ** | **E ** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="wavs/006461/gt.wav" controls preload></audio> | <audio src="wavs/006461/melgan.wav" controls preload></audio> | <audio src="wavs/006461/melgan_prls.wav" controls preload></audio> | <audio src="wavs/006461/pwgan.wav" controls preload></audio> | <audio src="wavs/006461/pwgan_prls.wav" controls preload></audio> |

Text: 目前，一种猫咪咖啡馆在上海悄然走红。

| ** A ** | ** B ** | ** C ** | ** D ** | **E ** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="wavs/005552/gt.wav" controls preload></audio> | <audio src="wavs/005552/melgan.wav" controls preload></audio> | <audio src="wavs/005552/melgan_prls.wav" controls preload></audio> | <audio src="wavs/005552/pwgan.wav" controls preload></audio> | <audio src="wavs/005552/pwgan_prls.wav" controls preload></audio> |

Text: 外界熟知的老故事是，哪怕买把扫帚，都得宗庆后批准。

| ** A ** | ** B ** | ** C ** | ** D ** | **E ** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="wavs/003746/gt.wav" controls preload></audio> | <audio src="wavs/003746/melgan.wav" controls preload></audio> | <audio src="wavs/003746/melgan_prls.wav" controls preload></audio> | <audio src="wavs/003746/pwgan.wav" controls preload></audio> | <audio src="wavs/003746/pwgan_prls.wav" controls preload></audio> |

Text: 我用皮带捆住腰，吊在巷道里的锚杆上，一直吊着。

| ** A ** | ** B ** | ** C ** | ** D ** | **E ** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="wavs/003271/gt.wav" controls preload></audio> | <audio src="wavs/003271/melgan.wav" controls preload></audio> | <audio src="wavs/003271/melgan_prls.wav" controls preload></audio> | <audio src="wavs/003271/pwgan.wav" controls preload></audio> | <audio src="wavs/003271/pwgan_prls.wav" controls preload></audio> |

Text: 其它团员按原定行程昨早离开澳门经拱北返回内地。

| ** A ** | ** B ** | ** C ** | ** D ** | **E ** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="wavs/002340/gt.wav" controls preload></audio> | <audio src="wavs/002340/melgan.wav" controls preload></audio> | <audio src="wavs/002340/melgan_prls.wav" controls preload></audio> | <audio src="wavs/002340/pwgan.wav" controls preload></audio> | <audio src="wavs/002340/pwgan_prls.wav" controls preload></audio> |

Text: 母亲哭着求儿子不要扔，一边拿笤帚扫。

| ** A ** | ** B ** | ** C ** | ** D ** | **E ** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="wavs/000954/gt.wav" controls preload></audio> | <audio src="wavs/000954/melgan.wav" controls preload></audio> | <audio src="wavs/000954/melgan_prls.wav" controls preload></audio> | <audio src="wavs/000954/pwgan.wav" controls preload></audio> | <audio src="wavs/000954/pwgan_prls.wav" controls preload></audio> |

Text: 多由毒蝇伞、豹斑毒伞等引起。

| ** A ** | ** B ** | ** C ** | ** D ** | **E ** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="wavs/000409/gt.wav" controls preload></audio> | <audio src="wavs/000409/melgan.wav" controls preload></audio> | <audio src="wavs/000409/melgan_prls.wav" controls preload></audio> | <audio src="wavs/000409/pwgan.wav" controls preload></audio> | <audio src="wavs/000409/pwgan_prls.wav" controls preload></audio> |
