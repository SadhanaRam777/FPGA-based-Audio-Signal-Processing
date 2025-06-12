# FPGA-based-Audio-Signal-Processing

The goal of this project is to use the DE1-SoC development board to design and construct a
Finite Impulse Response (FIR) filter that is especially suited for audio signal processing on an
FPGA platform. The principal goals were twofold: first, to enhance comprehension and
practical abilities in digital signal processing, FIR filters, and FPGA technology through
education; second, to accomplish the technical goal of effectively implementing a low-pass
FIR filter that is fully functional and integrated with a CODEC initialiser and S2P adaptor,
utilising the I2C protocol for efficient communication and control.
The process used an organised approach, starting with a thorough design step where the
specifications for the FIR filter were established. This was followed by a thorough
implementation phase where the FPGA was programmed using VHDL. Using the I2C protocol,
the CODEC was configured; an S2P adapter was created for serial-to-parallel data conversion;
and the FIR filter was designed to adhere to the necessary audio processing requirements.
The primary outcomes of the trials showed that the FPGA-based system effectively reduced
noise and improved signal clarity by filtering audio signals using the intended FIR filter. The
filter's response matched theoretical predictions after extensive testing, demonstrating the
system's capability to handle high-fidelity audio inputs and validating its performance.
In an overview, the project achieved its technical and instructional goals, strengthening the
real-world applications of digital signal processing theories and offering insightful information
about FPGA-based audio processing systems. In addition to serving as an excellent example
of how hardware and software can work together in signal processing applications, the FIR
filter's successful implementation on the FPGA platform also set the stage for further research
and development in the field of reconfigurable hardware design.
