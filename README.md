# angn-website
import React from 'react';
import { Card, CardContent } from '@/components/ui/card';
import { Button } from '@/components/ui/button';
import { FaFacebook, FaTwitter, FaInstagram, FaYoutube } from 'react-icons/fa';

export default function BusinessWebsite() {
  return (
    <div className="container mx-auto px-6">
      {/* Header */}
      <header className="text-center text-3xl font-bold mb-6">
        IT Vision Solutions
      </header>

      {/* Navigation */}
      <nav className="flex justify-center space-x-4 mb-8">
        <a href="#home" className="text-gray-700 hover:text-blue-600">Home</a>
        <a href="#about" className="text-gray-700 hover:text-blue-600">About</a>
        <a href="#services" className="text-gray-700 hover:text-blue-600">Services</a>
        <a href="#contact" className="text-gray-700 hover:text-blue-600">Contact</a>
      </nav>

      {/* Home Section */}
      <section id="home" className="mb-12">
        <Card>
          <CardContent>
            <h2 className="text-xl font-semibold mb-4">Welcome to IT Vision Solutions</h2>
            <p className="text-gray-600 mb-4">
              Empowering businesses with innovative ERP, AI-driven solutions, and technology services. Join us to transform your business for the digital future.
            </p>
            <Button className="mt-4">Learn More</Button>
          </CardContent>
        </Card>
      </section>

      {/* About Section */}
      <section id="about" className="mb-12">
        <Card>
          <CardContent>
            <h2 className="text-xl font-semibold mb-4">About Us</h2>
            <p className="text-gray-600">
              At IT Vision Solutions, we specialize in delivering custom software and ERP solutions tailored to your business needs. Our goal is to help you optimize operations, save costs, and achieve sustainable growth.
            </p>
          </CardContent>
        </Card>
      </section>

      {/* Services Section */}
      <section id="services" className="mb-12">
        <Card>
          <CardContent>
            <h2 className="text-xl font-semibold mb-4">Our Services</h2>
            <ul className="list-disc pl-5 text-gray-600">
              <li>Enterprise Resource Planning (ERP)</li>
              <li>HR & Payroll Management</li>
              <li>Customer Relationship Management (CRM)</li>
              <li>Complaint Management System</li>
              <li>Trading Management</li>
              <li>Tour & Travel Management</li>
              <li>Real Estate Management</li>
              <li>Hostel Management</li>
            </ul>
          </CardContent>
        </Card>
      </section>

      {/* Contact Section */}
      <section id="contact" className="mb-12">
        <Card>
          <CardContent>
            <h2 className="text-xl font-semibold mb-4">Contact Us</h2>
            <p className="text-gray-600 mb-2">Email: ayeshanisarghulamnabi7@gmail.com</p>
            <p className="text-gray-600 mb-2">Contact 1: +92 313 5051822</p>
            <p className="text-gray-600 mb-2">Contact 2: +92 334 5769700</p>
            <p className="text-gray-600 mb-2">Contact 3: +966 596 549025</p>
          </CardContent>
        </Card>
      </section>

      {/* Footer with Social Links */}
      <footer className="text-center mt-12">
        <p className="text-gray-600 mb-4">Follow us on:</p>
        <div className="flex justify-center space-x-4 text-2xl text-blue-600">
          <a href="https://www.instagram.com/itvisionsolutions/" target="_blank" rel="noopener noreferrer">
            <FaInstagram />
          </a>
          <a href="https://www.youtube.com/@ITVisionSolutions" target="_blank" rel="noopener noreferrer">
            <FaYoutube />
          </a>
          <a href="https://www.facebook.com/share/p/1BSriqq6df/" target="_blank" rel="noopener noreferrer">
            <FaFacebook />
          </a>
        </div>
        <p className="text-gray-600 mt-4">Visit our website: <a href="https://itvisionsolutions.com/" className="text-blue-600">itvisionsolutions.com</a></p>
      </footer>
    </div>
  );
}
