### Learning the coolest `Common Business Oriented Language` in the world.

Learning materials:
* https://riptutorial.com/cobol/topic/4728/getting-started-with-cobol

#### To install GnuCOBOL (formerly OpenCOBOL)

```bash
sudo apt-get install open-cobol
wget https://netcologne.dl.sourceforge.net/project/open-cobol/gnu-cobol/3.0/gnucobol-3.0-rc1.tar.xz
tar xf gnucobol-3.0-rc1.tar.xz
cd gnucobol-3.0-rc1/
./configure
make
cd ..
rm -fr gnucobol-3.0-rc1/ gnucobol-3.0-rc1.tar.xz
```

#### Build and Run

Build:

```bash
cobc -x -free <<source_file>>.cobc
```

Run:

```bash
./<<source_file>>
```
