<template>
        <div>
            <video 
            :src="videoSrc" 
            :autoplay="autoplay"
            :audioTracks="audioTracks"
            @ended='ended()'
            @error='error()'
            @play='play()'
            @pause='pause()'
            @load='load()'
            @canPlayType='canPlayType()'
            @addTextTrack='addTextTrack()'
            ></video>
        </div>
</template>

<script>
export default {
    name:'',
    props:{
        videoSrc: {
            type: String,
            default: 'http://www.w3school.com.cn/i/movie.ogg'
        },
        autoplay: {
            type: Boolean,
            default: false
            },
        audioTracks: {
            type:String,
            default:''
        },
        buffered: {
            type:Object,
            default:''
        },
        controller: {
            type:Object,
            default:''
        },
        controls: {

        },
        crossOrigin: {

        },
        currentSrc: {

        },
        currentTime: {

        },
        defaultMuted: {

        },
        defaultPlaybackRate: {

        },
        duration: {

        },
        ended: {

        },
        error: {

        },
        height: {

        },
        loop: {

        },
        mediaGroup: {

        },
        muted: {
            type: Boolean,
            default: false
        },
        networkState: {

        },
        paused: {
            type: Boolean,
            default: false
        },
        playbackRate: {

        },
        played: {

        },
        poster: {

        },
        preload: {

        },
        readyState: {

        },
        startDate: {

        },
        seekable: {

        },
        seeking:{

        },
        textTracks: {

        },
        videoTracks: {

        },
        volume: {

        },
        width: {

        }

    }
}
</script>



<style lang="less" scoped>

</style>






