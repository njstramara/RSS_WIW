# RSS_WIW 

.rsssl-ss-wrapper {
    overflow: hidden;
    width: 100%;
    height: 100%;
    position: relative;
    z-index: 1;
    float: left;
}

.rsssl-ss-content {
    height: 100%;
    width: calc(100% + 18px);
    padding: 0 0 0 0;
    position: relative;
    overflow-x: auto;
    overflow-y: scroll;
    box-sizing: border-box;
}

.rsssl-ss-content.rtl {
    width: calc(100% + 18px);
    right: auto;
}

.ss-scroll {
    position: relative;
    background: rgba(0, 0, 0, 0.1);
    width: 9px;
    border-radius: 4px;
    top: 0;
    z-index: 2;
    cursor: pointer;
    opacity: 0;
    transition: opacity 0.25s linear;
}

.ss-hidden {
    display: none;
}

.ss-container:hover .ss-scroll,
.ss-container:active .ss-scroll {
    opacity: 1;
}

.ss-grabbed {
    -ms-user-select: none;
    -moz-user-select: none;
    -webkit-user-select: none;
    user-select: none;
}
