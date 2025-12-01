---
layout: default
---

<script src="https://cdn.rawgit.com/download/polymer-cdn/1.5.0/lib/webcomponentsjs/webcomponents-lite.min.js"></script>
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
<link rel="stylesheet" href="thirdparty/trackswitch-js/trackswitch.min.css" />
<script src="https://code.jquery.com/jquery-3.2.1.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"></script>
<script src="thirdparty/trackswitch-js/trackswitch.min.js"></script>
<script type="text/javascript">
    var settings = {
        onlyradiosolo: true,
        repeat: true,
    };

    jQuery(document).ready(function() {
        jQuery(".player").trackSwitch(settings); 
    });
</script>

# Residual Learning for Neural Ambisonics Encoders
This website provides audio examples for the manuscript T. Deppisch, Y. Gao, M. Mittal, B. Stahl, C. Hold, D. Alon, and Z. Ben-Hur, "Residual Learning for Neural Ambisonics Encoders," 2025.

## Within-Domain Examples
### Multi-Source Mixtures
<div class="player">
    <ts-track title="Reference">
        <ts-source src="audio/mixture_0_label.wav"></ts-source>
    </ts-track>
    <ts-track title="Linear Encoder">
        <ts-source src="audio/mixture_0_linear_enc.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet">
        <ts-source src="audio/mixture_0_unetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet">
        <ts-source src="audio/mixture_0_uresidnetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet (mod.)">
        <ts-source src="audio/mixture_0_unet.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet (mod.)">
        <ts-source src="audio/mixture_0_uresidnet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiNet">
        <ts-source src="audio/mixture_0_ambinet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiResNet">
        <ts-source src="audio/mixture_0_ambiresidnet.wav"></ts-source>
    </ts-track>
</div>

<div class="player">
    <ts-track title="Reference">
        <ts-source src="audio/mixture_1_label.wav"></ts-source>
    </ts-track>
    <ts-track title="Linear Encoder">
        <ts-source src="audio/mixture_1_linear_enc.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet">
        <ts-source src="audio/mixture_1_unetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet">
        <ts-source src="audio/mixture_1_uresidnetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet (mod.)">
        <ts-source src="audio/mixture_1_unet.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet (mod.)">
        <ts-source src="audio/mixture_1_uresidnet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiNet">
        <ts-source src="audio/mixture_1_ambinet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiResNet">
        <ts-source src="audio/mixture_1_ambiresidnet.wav"></ts-source>
    </ts-track>
</div>

### Single-Source Examples
<div class="player">
    <ts-track title="Reference">
        <ts-source src="audio/reverberant_0_label.wav"></ts-source>
    </ts-track>
    <ts-track title="Linear Encoder">
        <ts-source src="audio/reverberant_0_linear_enc.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet">
        <ts-source src="audio/reverberant_0_unetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet">
        <ts-source src="audio/reverberant_0_uresidnetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet (mod.)">
        <ts-source src="audio/reverberant_0_unet.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet (mod.)">
        <ts-source src="audio/reverberant_0_uresidnet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiNet">
        <ts-source src="audio/reverberant_0_ambinet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiResNet">
        <ts-source src="audio/reverberant_0_ambiresidnet.wav"></ts-source>
    </ts-track>
</div>

<div class="player">
    <ts-track title="Reference">
        <ts-source src="audio/reverberant_1_label.wav"></ts-source>
    </ts-track>
    <ts-track title="Linear Encoder">
        <ts-source src="audio/reverberant_1_linear_enc.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet">
        <ts-source src="audio/reverberant_1_unetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet">
        <ts-source src="audio/reverberant_1_uresidnetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet (mod.)">
        <ts-source src="audio/reverberant_1_unet.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet (mod.)">
        <ts-source src="audio/reverberant_1_uresidnet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiNet">
        <ts-source src="audio/reverberant_1_ambinet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiResNet">
        <ts-source src="audio/reverberant_1_ambiresidnet.wav"></ts-source>
    </ts-track>
</div>

<div class="player">
    <ts-track title="Reference">
        <ts-source src="audio/reverberant_2_label.wav"></ts-source>
    </ts-track>
    <ts-track title="Linear Encoder">
        <ts-source src="audio/reverberant_2_linear_enc.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet">
        <ts-source src="audio/reverberant_2_unetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet">
        <ts-source src="audio/reverberant_2_uresidnetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet (mod.)">
        <ts-source src="audio/reverberant_2_unet.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet (mod.)">
        <ts-source src="audio/reverberant_2_uresidnet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiNet">
        <ts-source src="audio/reverberant_2_ambinet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiResNet">
        <ts-source src="audio/reverberant_2_ambiresidnet.wav"></ts-source>
    </ts-track>
</div>

## Out-of-Domain Dataset
<div class="player">
    <ts-track title="Reference">
        <ts-source src="audio/treble_0_label.wav"></ts-source>
    </ts-track>
    <ts-track title="Linear Encoder">
        <ts-source src="audio/treble_0_linear_enc.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet">
        <ts-source src="audio/treble_0_unetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet">
        <ts-source src="audio/treble_0_uresidnetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet (mod.)">
        <ts-source src="audio/treble_0_unet.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet (mod.)">
        <ts-source src="audio/treble_0_uresidnet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiNet">
        <ts-source src="audio/treble_0_ambinet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiResNet">
        <ts-source src="audio/treble_0_ambiresidnet.wav"></ts-source>
    </ts-track>
</div>

<div class="player">
    <ts-track title="Reference">
        <ts-source src="audio/treble_1_label.wav"></ts-source>
    </ts-track>
    <ts-track title="Linear Encoder">
        <ts-source src="audio/treble_1_linear_enc.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet">
        <ts-source src="audio/treble_1_unetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet">
        <ts-source src="audio/treble_1_uresidnetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet (mod.)">
        <ts-source src="audio/treble_1_unet.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet (mod.)">
        <ts-source src="audio/treble_1_uresidnet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiNet">
        <ts-source src="audio/treble_1_ambinet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiResNet">
        <ts-source src="audio/treble_1_ambiresidnet.wav"></ts-source>
    </ts-track>
</div>

<div class="player">
    <ts-track title="Reference">
        <ts-source src="audio/treble_2_label.wav"></ts-source>
    </ts-track>
    <ts-track title="Linear Encoder">
        <ts-source src="audio/treble_2_linear_enc.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet">
        <ts-source src="audio/treble_2_unetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet">
        <ts-source src="audio/treble_2_uresidnetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet (mod.)">
        <ts-source src="audio/treble_2_unet.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet (mod.)">
        <ts-source src="audio/treble_2_uresidnet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiNet">
        <ts-source src="audio/treble_2_ambinet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiResNet">
        <ts-source src="audio/treble_2_ambiresidnet.wav"></ts-source>
    </ts-track>
</div>

<div class="player">
    <ts-track title="Reference">
        <ts-source src="audio/treble_3_label.wav"></ts-source>
    </ts-track>
    <ts-track title="Linear Encoder">
        <ts-source src="audio/treble_3_linear_enc.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet">
        <ts-source src="audio/treble_3_unetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet">
        <ts-source src="audio/treble_3_uresidnetog.wav"></ts-source>
    </ts-track>
    <ts-track title="UNet (mod.)">
        <ts-source src="audio/treble_3_unet.wav"></ts-source>
    </ts-track>
    <ts-track title="UResNet (mod.)">
        <ts-source src="audio/treble_3_uresidnet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiNet">
        <ts-source src="audio/treble_3_ambinet.wav"></ts-source>
    </ts-track>
    <ts-track title="AmbiResNet">
        <ts-source src="audio/treble_3_ambiresidnet.wav"></ts-source>
    </ts-track>
</div>



